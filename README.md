# staticwebsite
This is a repository for a static website

## Hosting a Static Website

1. For Bucket name, enter: (website-name)
2. Verify the AWS Region is set to us-east-1 (if it is not, choose the us-east-1 Region)
3. In the Object Ownership section, select ACLs enabled, then verify Bucket owner preferred is selected.
4. Public access to buckets is blocked by default. Because the files in your static website will need to be accessible through the internet, you must permit public access by step 5.
5. Clear Block all public access, then select the box that states
6. I acknowledge that the current settings may result in this bucket and the objects within becoming public.
7. Enable the bucket versioning
8. Add tag if you want and enable bucket key if you sensitive information to store
9. Choose Create bucket.
10. Enable static website hosting
11. upload the files to the s3 bucket
12. Make all objects public
13. Test your website page is accessible.
