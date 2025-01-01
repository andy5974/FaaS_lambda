# FaaS_lambda


# -	Why do you think another log stream was created?

# Another new log is created when there is a new instance of an execution or trigger. Reasons are mainly to keep track of the events instance that are invoked.

# -	Can you tell what was the event that triggered the function? What was the file name?

# The event that triggered the function is when image file is uploaded to the S3 bucket, and this will trigger the function. lambda_function.py file

# -	Should you delete or overwrite the object in the bucket, work the function be triggered?

# We should delete the object in the bucket

# - What are ways to invoke the function without having an actual upload of an object to the S3 bucket? This is useful for development.

# using test event to trigger the event and check cloudwatch for log stream for development.