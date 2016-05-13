# Fit build

Build core package and main ext packages into one jar ---- fitall.jar

         ant -f build-all.xml
         
* Run fit

         java -jar fitall.jar <-script|case> [--project=case dir] [--variable=value]
         
         example: java -jar fitall.jar -case --project=d:\testproject1 --user=zhou --pass=zhou
         
* test fit features

         1. git clone https://github.com/fastj/fit-testcases.git
         2. run fit with --project=BaseDir\fit-testcases

