# Testing Links for Correlation Recorder

## Introduction

In the most recent implementations of (Siebel's JMeter Plugin)[https://github.com/Blazemeter/SiebelPlugin] (probably Correlations Recorder renamed) we will be adding the possibilty of sharing the users Templates as Repositories, to be used on different enviroments and platforms. 

Before that release come's to the public, we will be using this GitHub's Repo to test and store the "Repositories" that contains the templates.

Basically, any link can be used to test the app but, they need to be used in their "raw" versions, the pure "JSON" file, to be able to work, at this stage.

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
