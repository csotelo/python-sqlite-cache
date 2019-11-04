#!/usr/bin/env python

import sys
import sqlite_cache

from setuptools import setup, find_packages


extra = {}
if sys.version_info >= (3,):
    extra['use_2to3'] = True
    extra['convert_2to3_doctests'] = ['README.md']

CLASSIFIERS = [
    'Development Status :: 5 - Production/Stable',
    'Intended Audience :: Developers',
    'License :: OSI Approved :: MIT License',
    'Natural Language :: English',
    'Operating System :: OS Independent',
    'Programming Language :: Python',
    'Topic :: Software Development :: Libraries :: Python Modules'
    ]

KEYWORDS = 'sqlite cache'

setup(name='python-sqlite-cache',
      version=sqlite_cache.__version__,
      description="""SQLite cache for Python.""",
      long_description=open('README.md').read(),
      author=sqlite_cache.__author__,
      url='https://github.com/csotelo/python-sqlite-cache',
      packages=find_packages(),
      download_url='http://pypi.python.org/python-sqlite-cache/',
      classifiers=CLASSIFIERS,
      keywords=KEYWORDS,
      zip_safe=True,
      install_requires=[''],
      py_modules=['python-sqlite-cache']
)
