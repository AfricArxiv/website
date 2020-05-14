from dateutil import parser
from flask import Flask, request, Response
from feedgen.feed import FeedGenerator
from unidecode import unidecode
import requests
import json
import re

app = Flask(__name__)

# how to address issue of mappings 
