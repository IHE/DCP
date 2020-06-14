# Dynamic Care Planning

Dynamic Care Planning implementation guide

> This repository was put together to help explore capabilities for FHIR build tooling to support IHE supplement development. Since it was created, there have been several improvements in the FHIR publication tooling, including the use of templates. This IG should be updated to use templates, and specifically the [IHE Supplement](https://github.com/IHE/supplement-template) template. In addition, the IG should be reviewed for adherence to IHE [Guidance on Writing Profiles of FHIR](https://wiki.ihe.net/index.php/Guidance_on_writing_Profiles_of_FHIR)

Commits to this repository will automatically trigger a new build of the IG, which will then be published to the following location:

[http://build.fhir.org/ig/IHE/DCP](http://build.fhir.org/ig/IHE/DCP)

Build log is available here:
[http://ig-build.fhir.org.s3-website-us-east-1.amazonaws.com/logs/IHE/DCP](http://ig-build.fhir.org.s3-website-us-east-1.amazonaws.com/logs/IHE/DCP)

Full debugging information is available here:
[http://build.fhir.org/ig/IHE/DCP/debug.tgz](http://build.fhir.org/ig/IHE/DCP/debug.tgz)

## Local Build

The HL7 IG Publisher is committed to this repository to make building as easy as possible. To build locally, clone the repository and issue the following command in the root:

    java -jar "org.hl7.fhir.publisher.jar" -ig ig.json

## Dependencies

Before the instructions in the above "Local Build" section will work, you
need to install several primary dependencies.

### Java

Go to [http://www.oracle.com/technetwork/java/javase/downloads/](
http://www.oracle.com/technetwork/java/javase/downloads/) and download the
latest (version 8 or higher) JDK for your platform, and install it.

### Ruby

Jekyll requires Ruby version 2.1 or greater.  Depending on your operating
system, you may already have Ruby bundled with it.  Otherwise, or if you
need a newer version, go to [https://www.ruby-lang.org/en/downloads/](
https://www.ruby-lang.org/en/downloads/) for directions.

### Jekyll

Go to [https://jekyllrb.com](https://jekyllrb.com) and follow the
instructions there, for example `gem install jekyll bundler`.  The end
result of this should be that the binary "jekyll" is now in your path.

