# kinesis-demo
kinesis-demo-showing issues with concurrent execution

The issue is that both of these consumers do not seem to be working concurrently 
and as soon as the application starts, one of these two start polling and receiving records but not both.
