# Assignment3.python
- Title: "NFT Aggregator"
- Installation: 1)Psycopg2 is the most popular PostgreSQL database adapter for the Python programming language.

                2)Flask provides configuration and conventions, with sensible defaults, to get started. 

                4)render_template is a Flask function from the flask.templating package. render_template is used to generate output from a template file based on the                       Jinja2 engine that is found in the application's templates folder.

                6)The request object is a Request subclass and provides all of the attributes Werkzeug defines plus a few Flask specific ones.

                8)from flask import Flask
                  from flask import render_template
                  from flask import request
                  import psycopg2
                  import requests
- Usage: When User provides an address of an NFT and presses the button, it should show full information about that NFT and store all the data inside the Postgres                Database.
- Examples: https://solana-gateway.moralis.io/api/#/nft/getNFTMetadata
