Bug: search_movie() gave NoneType error during testing with message "NoneType is not iterable". 
What happened: TMDB was not feeding the right info, and updating the function to have some printouts helped fix the issue.
Status: Bug was fixed after retried. Added some printouts to check to make sure json was being sent by TMDB API.