Erlang S3 Library
==================

Basic gen_server implementation.  

Be sure to define these as needed  
-define(ACCESS_KEY, "ACCESS_KEY").  
-define(SECRET_KEY, "SECRET_KEY").  
-define(AWS_S3_HOST, "s3.amazonaws.com").  
-define(TIMEOUT, infinity).  
-define(CHUNK_SIZE, 1024 * 5).  

Basic Operations  
{put_file, Local_file, Remote_file, Acl_temp}  
{get_file, Resource, Local_file}  
{change_bucket, Bucket}  
{create_bucket, Bucket}  
{list_keys, Resource}  
{get_acl, Resource}  
{set_acl, Resource, ACL_temp}  
{make_link, Expire_time, Resource} Make an external expiring link to a S3 resource
