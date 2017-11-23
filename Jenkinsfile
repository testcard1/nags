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
   office365ConnectorSend   message:'Message from Multibranch pipeline', webhookUrl:'https://outlook.office.com/webhook/d08cd814-52ae-47db-876b-9f9551e83f30@72f988bf-86f1-41af-91ab-2d7cd011db47/JenkinsCI/3400c97bff784763a2b4f95c299b9819/11a97ad3-e780-471d-abd5-0abddae8e624', color: 'd00000'
   // Run the maven build
}



