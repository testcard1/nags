node {
   // Mark the code checkout 'stage'....
   stage 'Checkout'

   // Checkout code from repository
   checkout scm

   // Get the maven tool.
   // ** NOTE: This 'M3' maven tool must be configured
   // **       in the global configuration.

   // Mark the code build 'stage'....
   stage 'Build'
   office365ConnectorSend   message:'Message from Multibranch pipeline', webhookUrl:'https://outlook.office.com/webhook/659b3fd7-dc4b-4857-b072-db85e2924d23@72f988bf-86f1-41af-91ab-2d7cd011db47/JenkinsCI/0e762eb79cfa4a48bb8815a0b676f094/659b3fd7-dc4b-4857-b072-db85e2924d23', color: '800000'
   // Run the maven build
}



