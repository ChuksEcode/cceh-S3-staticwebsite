# staticwebsite
This is a repository for a static website

## Hosting a Static Website

1. For Bucket name, enter: (website-name)
2. Public access to buckets is blocked by default. Because the files in your static website will need to be accessible through the internet, you must permit public access.
3. Verify the AWS Region is set to us-east-1 (if it is not, choose the us-east-1 Region)
4. In the Object Ownership section, select ACLs enabled, then verify Bucket owner preferred is selected.
5. Clear Block all public access, then select the box that states
6. I acknowledge that the current settings may result in this bucket and the objects within becoming public.
7. Choose Create bucket.
8. Enable static website hosting
9. upload the files to the s3 bucket
10. Make all objects public
11. Test your website page is accessible.
