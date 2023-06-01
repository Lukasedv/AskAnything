# AskAnything

Tweaked original repo to work with Azure instead - also changed site to tampere.fi

To work with Azure you need to export the following env variables:

openai.api_type = os.environ["OPENAI_API_TYPE"]
openai.api_key = os.environ["OPENAI_API_KEY"]
openai.api_base = os.environ["OPENAI_API_BASE"]
openai.api_version = os.environ["OPENAI_API_VERSION"]