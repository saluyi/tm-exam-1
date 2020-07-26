# tm-exam-1
`please fork this project to start this exam.`
## requirement
* create a spring boot applcation
* create a restful API /SumbitZip 
  * API can receive zip file (you can generate any zip file by yourself)
  * save file in local
  * send file path to AWS SQS \
  `SQS name: gtoc-exam-queue` \
  `SQS region: us-east-1`
* create a SQS Listener
  * receive zip file path from queue
  * extracte files from zip
  * get extracteed files info \
  `fileName,filePath,fileSize,fileSha1`
