#!/usr/bin/env groovy
//Leave the above line alone.  It identifies this as a groovy script.

String nodeLabel = 'dcaf'
List<String> lvVersions = ["2016"]
String sourceVersion = '2016'
BuildType buildType = BuildInformation.BuildType.NiBuild

def buildInfo = new BuildInformation(nodeLabel, sourceVersion, lvVersions, buildType)
buildPipeline(buildInfo)

//buildPipeline(getCommonBuildInformation())
