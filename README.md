# csv-uploader
# The following will be a provide to end users as a solution when uploading CSV's
# currently the process is still heavy for those users looking to evaluate Keen in a trial basis
# or to users that would like a simple way to upload smaller batches of events via a CSV file
#
# This will be a UI abstraction to CLI process.
# https://github.com/keen/keen-cli
#
# # POST Example via Curl Request
# $ curl https://api.keen.io/3.0/projects/PROJECT_ID/events/COLLECTION_NAME \
#    -H "Authorization: WRITE_KEY" \
#    -H 'Content-Type: application/json' \
#    -d '{
#      "key": 123
#    }'
#
# GET Request via Curl
#
# curl "https://api.keen.io/3.0/projects/PROJECT_ID/events/COLLECTION_NAME?api_key=WRITE_KEY&data=ENCODED_DATA"
#
# Successful Response
# {
#  "created": true
# }
#
#
#
#
#
