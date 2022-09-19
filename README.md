# LISS-harvester
You can now harvest both EASY data (DDI) and LISS (DC) with the setup. It is now set to havester EASY  by default, modify the `.env` file to change it. 

The records are chopped into individual XML files and stored in the `rec` folder of the data storeage folder, which can be set in `.env` as well. 

For now, it will be some standalone scripts. Eventually, it should become recipe or part of framework. 

### OAI-PMH (DC only)
https://www.oai-pmh.centerdata.nl/lissdata/oai2.php?verb=ListRecords&metadataPrefix=oai_dc

### PHP XML
https://www.oai-pmh.centerdata.nl/lissdata/question_texts.php?id=24

The output of this process can be used by the SEMAF-Client

To run this tool, simply `docker-compose up`

