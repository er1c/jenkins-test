node {
   stage 'Checkout'

   checkout scm

   stage 'Build'

   sh "${tool name: 'sbt', type: 'org.jvnet.hudson.plugins.SbtPluginBuilder$SbtInstallation'}/bin/sbt compile test"
}