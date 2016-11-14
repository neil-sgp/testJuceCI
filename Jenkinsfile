#!/usr/bin/env groovy
/* Notes
*/

node('Windows7')
{
stage 'Checkout'
  checkout scm

stage 'Configuration'
  bat "echo Build number ${env.BUILD_NUMBER}"

stage 'Report'
  bat "echo Done"
}
