# -*- coding: utf-8 -*-
"""
Created on Sun Aug 15 21:28:11 2021

@author: GU20005915
"""

from flask import Flask
app = Flask(__name__)
  
@app.route('/hello/<name>')
def hello_name(name):
   return 'Hello %s!' % name
  
if __name__ == '__main__':
   app.run()
