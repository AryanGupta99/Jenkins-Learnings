-> When Developers are committing changes to the shared repository like github and any other.
-> Now, Jenkins server will pull the committed code at regular intervals.
-> It will build the package  and notify the developers about build result.

*Steps for Jobs creation in Jenkins*
step 1 -> We will creat job 1 for the compilation of the Source Code.
step 2 -> jenkins server will pull the code and prepare build.
step 3 -> Create another job 2 for reviewing the build job.
step 4 -> create the job 3 for testing the code which was packaged by build phase.

*But all of the above are separate freestyle jobs and not a single pipeline that means for building each time we have to manually go and click the build now button which will take a lot time for long projects.

* so we will create a automation pipeline for this three jobs and deployment*
	
-> create a pipeline
-> add build stages like one after the another if build is completed
-> then configure the options according the organization requirements

