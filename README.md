# Cloudera Development Kit Examples

The CDK Examples project provides examples of how to use the CDK.

Each example is a standalone Maven module with associated documentation.

## Basic Examples

* `dataset` shows how to create datasets and perform streaming writes and reads over them.
* `logging` is an example of logging events from a command-line programs to Hadoop via Flume, using log4j as the logging API.
* `logging-webapp` is like `logging`, but the logging source is a webapp.

## Advanced Examples

* `demo` is a full end-to-end example of a webapp that logs events using Flume and performs session analysis using Crunch and Hive.

## Getting Started

The easiest way to run the examples is on the
[Cloudera QuickStart VM](https://ccp.cloudera.com/display/SUPPORT/Cloudera+QuickStart+VM),
which has all the necessary Hadoop services pre-installed, configured, and
running locally.

The current examples run on version 4.3.0 of the QuickStart VM.

Checkout the latest [branch](https://github.com/cloudera/cdk-examples/branches) of this repository in the VM:

```bash
git clone git://github.com/cloudera/cdk-examples.git
cd cdk-examples
```

(Alternatively, if you want to use the master branch, then build the [CDK](https://github.com/cloudera/cdk) locally first.)
Then choose the example you want to try and refer to the README in the relevant subdirectory.