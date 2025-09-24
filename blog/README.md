# Blog 

## Generate

To generate a lab use the following:

1. Enter the following command:

   ```
   curl -X POST http://localhost:8081/ollama/chat  \
     -H "Content-Type: application/json" \
     -d '{"name":"Alice","role":"system","message":"Creating a GCE Instance on Google Cloud."}'
   ```

   __EXPECTED OUTPUT__

   All generated output is located in the `labs` folder.
   

## Review

TBC
