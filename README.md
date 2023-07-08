## Bincom Tech Club WhatsApp Group Chat Analysis

Extracting, cleaning and analysing WhatsApp group chat data as well as creating an interactive report in PowerBI

## Introduction

I have always wanted to work on this project because it involves real data that is personal. The documentation includes:
- Data Gathering & Transformation
- Report Requirement
- Data & Report Limitation
- Conclusion

## Data Gathering & Transformation

To get the WhatsApp chat data, I simply exported the chat from the WhatsApp group by navigating to the ellipsis at the top right corner of the group chat and selecting "Export Chat".  The exported chats needed to be tansformed for ease of analysis and it was done using Power Query. Here is the Power Query Script to [Clean the WhatsApp Text file](/CleanWhatsAppData.pq.txt)

## Report Requirement

While planning for this project the initial purpose of creating the report was to see the overall trend of conversations on the group and identify what period of time the most conversations took place. However, during the report design I was also interested in creating a report that lets the individual members of the group see their level of activity on the group over time. In summary, the report requirement was provide an overall trend of group activity and let each group member see their activiity.

## Data & Report Limitations

- The exported data does not include all messages from the inception of the group chat.
- From the data there is no way to identify who a message was responding to except the person was directly tagged.
- The data transformation and report does not provide data on who a message was in response to.
- Parts of a message might be ommitted due to some needed fix in the Power Query Script.

## Conclusion

This was a fun project to work on. Hopefully, the Power Query Script and documentation would help you replicate on your own data.

You can explore the interactive version of the report to see the full functionality and user experience through the link provided below.
[PowerBI Report](https://app.powerbi.com/view?r=eyJrIjoiMDFlMjc1NDQtYTRlOS00YjBkLTkxYjgtNjk2NTVhMzFlMTU4IiwidCI6IjQzZjFiNDVlLTIwODgtNGE4NS05MTE3LWM1ODhiODdiNDQwYSJ9)
