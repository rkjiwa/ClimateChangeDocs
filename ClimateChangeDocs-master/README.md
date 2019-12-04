==================================================
v0.2 2019-10-10

Two new folders have been created - for documents not yet examined, and for documents that have been examined, do contain climate change information, but for which useful actions are not present.
==================================================
v0.1 2019-10-08

The delimiter is "|".

The basic unit of an action is a sentence. Don't worry about possible duplication, that will be dealt with outside of the ML project via a search engine, human workflow process, or similar. For now just find all sentences that seem to indicate an action or decision that a user can or must make.

Column headings:
action = what is the exact text of the sentence?
action_type = is this action intended to help with risk avoidance, risk mitigation (reducing damage), risk transferrence (making it someone else's problem), planning, adaptation to an ongoing issue, or for disaster recovery?
disaster_type_title = what kind of disaster is this?
disaster_type_detail = more information on the disaster (ex a particular type of flooding or weather event)
doc_page = what PDF page number (not the printed page number) that the action sentence is on?
doc_path = what is the path to the document (in git repository)
doc_title = what is the document title?
doc_publisher = who published this document?
date_added = when was this row added to git (to help track ongoing additions to the repo)
context_geography = Does this action apply anywhere? If not, which geographic jurisdictions does it apply to (Country, Province/state, city)
context_usertype = Which type of Climate Change Impact Portal (CCIP) user is this action intended for?