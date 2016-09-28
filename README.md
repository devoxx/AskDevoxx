# AskDevoxx
Bot client and Watson REST service for AskDevoxx

# Provide missing info for application.properties file 

askdevoxx.workspaceId=PROVIDE CONVERSATION SPACE ID
askdevoxx.conversationUsername=PROVIDE CONVERSATION USERNAME
askdevoxx.conversationPassword=PROVIDE CONVERSATION PASSWORD
askdevoxx.conversationUrl=https://gateway.watsonplatform.net/conversation/api
askdevoxx.retrieveUsername=PROVIDE RETRIEVE & RANK USERNAME
askdevoxx.retrievePassword=PROVIDE RETRIEVE & RANK PASSWORD
askdevoxx.retrieveClusterName=PROVIDE CLUSER NAME
askdevoxx.retrieveCollectionName=articles
askdevoxx.retrieveUrl=https://gateway.watsonplatform.net/retrieve-and-rank/api/v1/solr_clusters/

askdevoxx.tmpFileStorageLocation=./

# Speech to text credentials

speech.username=<PROVIDE_SPEECH_TO_TEXT_USERNAME>

speech.password=<PROVIDE_SPEECH_TO_TEXT_PASSWORD>

[![Deploy to Bluemix](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy?repository=https://github.com/devoxx/AskDevoxx)

After the application is deployed, launch the conversation tooling and import the workspace.json available in this repository to try the sample conversations.
