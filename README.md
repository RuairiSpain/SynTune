# SynTune
Building LLM finetuning datasets


WeWe askask GPT4GPT4 toto generategenerate QQ&AQQ&A templatestemplates forfor eacheach wikiWikipedia tablet able.able. ThenThen parseparse thethe htmlhtml tables inin GoGo andand populatepopulate millionsmillions ofof NLPNLP QQ&AQQ&A recordsrecords withwith WMFWMF structuredstructured datad ata.thisata.this willwill makemake itit readyready toto ingestingest inin thethe pre-training oror finetuningfinetuning stagestage forfor LLMsL LMs.

WellWe'll havehave hugehuge newnew datasetsdatasets readyready toto gog o!

Proposed Output:https://en.m.wikipedia.org/wiki/Premier_League


For the "Current Premier League managers" table from the Wikipedia page, you can create question and answer pairs for each column header as follows:

1. **Name**:
   - Question: "Who is the manager of [Team Name]?"
   - Answer: "The manager of [Team Name] is ___."

2. **Country of Birth**:
   - Question: "From which country does [Manager's Name], the manager of [Team Name], originate?"
   - Answer: "[Manager's Name] originates from ___."

3. **Date of Birth**:
   - Question: "What is the birth date of [Manager's Name], the manager of [Team Name]?"
   - Answer: "The birth date of [Manager's Name] is ___."

4. **Team**:
   - Question: "Which team is managed by [Manager's Name]?"
   - Answer: "[Manager's Name] manages ___."

5. **League**:
   - Question: "In which league does [Manager's Name] manage [Team Name]?"
   - Answer: "[Team Name] is managed in the ___."

6. **Date of Appointment**:
   - Question: "When was [Manager's Name] appointed as the manager of [Team Name]?"
   - Answer: "[Manager's Name] was appointed on ___."

7. **Time in Charge**:
   - Question: "How long has [Manager's Name] been in charge of [Team Name]?"
   - Answer: "[Manager's Name] has been in charge for ___."

These templates allow you to automate the fill-in-the-blank process using the data from each row, tailored to the specific column in the table. Each blank ("___") will be filled with the relevant data from the table for each specific manager. This approach ensures that the questions are clear and directly related to the information available in the table.
I'd like you to look at this page and read the text around each table

https://en.m.wikipedia.org/wiki/Premier_League

What I'd like you to do is read the table that starts with "Current Premier League managers" read each column header and generate question and answer pair with a fill in the blank answer template. Later I'll automate the  fill in the blank template with all the data from each row.

Prompt:

I need you to write the questions for each column in that table. And the template answer with a blank for the cell data 