node('windows7')
{
stage 'Checkout'
  checkout scm

stage 'Configuration'
  bat "echo Build number $(env.BUILD_NUMBER)"

stage 'Report'
  bat "echo Done"
}
