# Faceswap-API
Instantly enhance your apps with our fast and easy-to-use [Faceswap API](https://piapi.ai/faceswap-api), creating remarkable customised images that will amaze your users!

<br><br>
<img src="https://github.com/PiAPI-1/Faceswap-API/assets/173328932/4552588e-9745-4684-b0ec-d4e3307456b2" alt="screenshot of the Midjourney API page from PiAPI" width="95%"/>

<br><br>

<h2>Features</h2>
<ol>
  <li>Cost Effective</li>
  <li>Low Latency</li>
  <li>Supports High Concurrency</li>
  <li>Easy Setup and Integration.</li>
  <li>Asynchronous</li>
  <li>Automatic face detection</li>
  <li>Bulk generation</li>
  <li>Standard RESTful API</li>
  <li>Webhook</li>
</ol>

<br><br>


<h3>Pricing</h3>

<ul>
  <li>Standard: $0.01/call</li>
  <li>Custom Dedicated Deployment: Contact us via email!</li>
</ul>

<br>

<h2>Usage Steps</h2>

<h3>Pay-as-you-go Option</h3>

<ul>
  <li>Register for PiAPI's Workspace using your GitHub account.</li>
  <li>Obtain your API KEY from our <a href="https://app.piapi.ai/">Workspace</a></li>
  <li>Start coding right away!</li>
</ul>

<br>

<h4>Sample API Calls (using cURL)</h4>

<br>

<p>Create a Faceswap call</p>

```
curl --request POST \
  --url https://api.piapi.ai/api/face_swap/v1/async \
  --header 'Accept: application/json' \
  --header 'Content-Type: application/json' \
  --header 'X-API-Key: {{x-api-key}}' \
  --data '{
  "target_image": "Superman.png",
  "swap_image": "Leonardo_Dicaprio.png",
  "result_type": "url"
}'
```

<p>Response</p>

```
{
    "code": 200,
    "data": {
        "task_id": "record_this_taskID"
    },
    "message": "success"
}
```

<br>

<p>Fetch the Faceswap call</p>

```
curl --request POST \
  --url https://api.piapi.ai/api/face_swap/v1/fetch \
  --header 'Accept: application/json' \
  --header 'Content-Type: application/json' \
  --header 'X-API-Key: {{x-api-key}}' \
  --data '{
  "task_id": "Insert_the_taskID_here"
}'
```

<br>

<p>Response - Check out our <a href="https://piapi.ai/docs/faceswap-api/fetch">documentation</a> for more information!</p>

<br><br>

<h2>Contact us</h2>
<p>Email: <a href="mailto:contact@piapi.ai">contact@piapi.ai</a></p>

<br>
