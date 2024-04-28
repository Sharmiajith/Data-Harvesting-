YouTube Data Harvesting & Warehousing using Pandas,SQL and Streamlit


## API Reference

  GET /api/items


| Parameter | Type     | Description                |

| part | `string` | contentdetails,statisics,snippet |

#### Get item

  GET /api/items/{id}

| Parameter | Type     | Description |

| `id`      | `string` | Youtube channel id |
GET /api/items/{id}
| Parameter | Type     | Description |

| `id`      | `string` | Video id |
GET /api/items/{id}
| Parameter | Type     | Description |

| `id`      | `string` | comment  id |





## Installation

Installion in my project
pip install google-python-api-client
pip install mysql.connector
pip install streamlit
pip install pandas
pip install sqlalchemy


import googleapiclient.discovery
import mysql.connector
import pandas as pd
from sqlalchemy import create_engine
import re
from googleapiclient.errors import HttpError
    
## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

https://console.cloud.google.com/cloud-resource-manager
In this program first we get a api key from google developer console. After completing this first process  we get a reference from youtube documentation for starting the project and collect 10 different youtube channels information(Channel name,video count, comments,subscriber count, playlist id ).
All the details are run in jupyter notebook after completing this main process we have to run the program in streamlit.
If we run the program in streamlit means convert the jupter notebook file to python environment.