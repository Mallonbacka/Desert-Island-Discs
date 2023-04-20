This repository contains my attempt to find all the disabled people who have appeared on the BBC's Desert Island Discs.

The notebook contains the process, written in Python, and writes the results to a CSV file. 

## Limitations

- Data only go up to the end of 2021. Using mor recent data would be a little more work, as the more recent data files don't include Wikipedia links. For now I've looked through the last two years manually.
- Depending where I run the notebook, Sinéad Burke may or may not appear in the list. I beleive this is related to character encoding. Again, I can handle this one manually for now, but I hope to figure it out so I can be sure no more are missed. 
- At the moment, we load the same ~3K articles twice, which is unnecessary and slow. Since the code was designed to be run about once a year, I'm not rushing to fix it. 

