# Example Health - Node.js Database Adapter for Cloudant

Used in IBM Solution Tutorial: [Deploy microservices with OpenShift](https://cloud.ibm.com/docs/solution-tutorials?topic=solution-tutorials-openshift-microservices)


For local testing:

1. Set `CLOUDANT_URL` to Cloudant connection details.

    ```
    export CLOUDANT_URL=https://username:pass.cloudantnosqldb.cloud
    ```
    or create `credentials.json` in the root directory:
    ```
    {
        "url": "https://username:pass.cloudantnosqldb.cloud"
    }
    ```

1. Run `npm start`.
