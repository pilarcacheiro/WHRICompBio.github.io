# Computational Biology Meetings

This repo defines the web page for the WHRI computational biology Friday meetings. 

The web pages are generated automatically using jekyll. To keep them up 
to date and in working order, some **regular maintenance is required**.



&nbsp;
## Schedule

The schedule for the meetings is defined in a csv file located in the `_data`
directory,

```
_data/schedule.csv
```

To edit the schedule, open the file in a github page, modify the contents, and 
commit the changes. The

**Note:** The file should be maintained in chronological order.



&nbsp;
## Meeting agenda

The agenda for the upcoming meeting is defined in a markdown file located at the 
root of the repo, 

```
index.md
```

To add items to the agenda, open the file, modify the contents, and commit the 
changes. The changes will automatically appear on the web page (wait a minute, 
then refresh the page using F5 or Ctrl-F5).

The agenda must be cleared manually after a meeting to make room for new 
discussion topics.

**Note:** Do not change or delete the yaml header in this file.



&nbsp;
## Summaries of past meetings

All past meetings should be summarized in markdown files in the `_posts` 
directory, e.g. 

```
_posts/2018-01-26-index.md
```

There should be one file for each past meeting. These files must be created 
manually to reflect the topics discussed during the meeting.

**Note:** The post filename should follow the format shown. 

**Note:** The post file should contain a yaml header; see headers from 
existing posts.

