# Testing Links for Correlation Recorder

## Introduction

We are using this Repo to store the "Correlation Templates Repositories" and the "Correlation Templates" asociated to them. Basically, any link can be used to test the app but, they need to be used in their "raw" versions to be functional.

Its expected that the future users use their very own Web Link to store those files.

## Usage

To test the download of the "Base Repository", the link should follow the following structure:

`https://raw.githubusercontent.com/<UserRepo>/<Repository>/<rute_to_the_repository_file>.json`

For example: 

<pre>https://raw.githubusercontent.com/RicardoPoleo/JMeter-Correlation-Templates-Repository/master/base-repository.json</pre>

This file contains the Repository file:

```
{
  "siebel": { "versions": [ "1.0", "1.1" ] },
  "wordpress": { "versions": [ "1.0" ] }
}
```

Which will be used to build the urls to download the Siebel's and Wordpress's Templates
