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
   office365ConnectorSend   message:'Message from Multibranch pipeline', webhookUrl:'https://outlook.office.com/webhook/2daad73a-0c16-4579-9ca5-7d492fa887cd@72f988bf-86f1-41af-91ab-2d7cd011db47/JenkinsCI/a2a0b36327634ef8858f3faba74173b7/659b3fd7-dc4b-4857-b072-db85e2924d23', color: '800000'
   // Run the maven build
}



