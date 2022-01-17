#!/usr/bin/env groovy

String tarquinBranch = "TNC/tnc-o-tracking#2413"

library "tarquin@$tarquinBranch"

pipelineLmctl {
  pkgInfoPath = 'kubedriver/pkg_info.json'
  applicationName = 'kubedriver'
  releaseArtifactsPath = 'release-artifacts'
  attachDocsToRelease = true
  attachHelmToRelease = true
}
