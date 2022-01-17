#!/usr/bin/env groovy

String tarquinBranch = "TNC/tnc-o-tracking#3380"

library "tarquin@$tarquinBranch"

pipelinePy {
  pkgInfoPath = 'kubedriver/pkg_info.json'
  applicationName = 'kubedriver'
  releaseArtifactsPath = 'release-artifacts'
  attachDocsToRelease = true
  attachHelmToRelease = true
}
