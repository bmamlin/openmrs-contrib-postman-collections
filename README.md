Collections of [Postman](https://www.getpostman.com) REST calls 
for testing of RESTful APIs.

If you have Postman installed, you can import a `.postman_collection`
file directly.

Run tests using Docker:

```bash
docker run -t postman/newman_ubuntu1404 \
  --url="https://raw.githubusercontent.com/bmamlin/openmrs-contrib-postman-collections/master/platform-2.0-tests.postman_collection"
```
