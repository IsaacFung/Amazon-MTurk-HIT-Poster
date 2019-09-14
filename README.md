# A Template for Posting HITS With External Questions in Amazon Mechanical Turk

A Python script that serves as a general template for Python users to follow when posting HITS with External Questions to Amazon Mechanical Turk. The script is written in Python and uses the Boto3 and argpares libraries to enables users to make posting multiple variations of HITS from the command line without code duplication of the script itself.

In order to successfully post a HIT, the user needs 3 files:

1. HIT_posting_script.py
2. question.xml
3. Some file storing the key_id and access_key in a file with a ".key" ending; the default used by the script is mykey.key

The user should also needs to add URLs to the HIT_posting_Script. A simple recommended way is hosting these URLs using Heroku.

The user simply needs to get a key_id and access_key by creating an AWS account if they have not done so already.
