# AITAandGender
The data in this research specifically focuses on romantic/ relationship advice and ethical judgments in online advice columns with regards to gender. This data has been pulled from r/AmITheAsshole with Communalytic. To pull relevant data, search queries with relevant terms were used. After the data is pulled, toxicity, sentiment, and topic analysis has been run by Communalytic. Upon downloading, it has been cleaned to remove identifying information and user flairs. The data is separated into three sheets: Original Data (includes all downloaded data), Submissions (only posts categorized as submissions), and Comments and Replies (only posts categorized as a comment or reply to a submission). The Submissions sheet is filtered to only include those that are not by mods, have a consensus, include the age and gender of the poster, and a relevant topic (the posts filtered out are still included in Original Data). The topic of the post, age and gender of the poster, and the age and gender of those involved (when mentioned) are manually input into the sheet. Comments and Replies are filtered to only include those that are not by mods and threads that are in response to submissions that have not been filtered. 

The search queries used on Communalytic/ key terms searched for are: "boyfriend OR girlfriend OR partner OR spouse OR wife OR husband OR date OR relationship OR sex OR romantic OR romance OR dating OR married OR marry OR fiance OR engaged OR engagement OR propose OR proposed OR break up OR broke up OR cheat OR cheated OR hooking up"

The process to clean data is outlined below:
1.	Remove columns: C (author), L (user_flair), and links
2.	Rename sheet “Original data,” make “Submission” sheet and “Comments and Replies” sheet
In _Submission_ sheet
3.	Reorder and add columns
Id, date, submission flair, title, topic, poster gender, poster age, gender of involved, age of involved, then the rest (make text bigger and wrap)
4.	Remove submissions without submission flair (Filter, select Asshole, Not the asshole, and Everyone sucks)
5.	Remove submissions with AUTOMOD or MOD
6.	Read
a.	Add poster gender 
b.	Add poster age
c.	Add gender of involved
d.	Add age of involved
e.	Add topic 
7.	Remove posts without user gender or age
In _Comments and Replies_ sheet
8.	Remove threads replying to removed posts 
9.	Remove posts with AUTOMOD or mod as poster ()
