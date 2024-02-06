# Bilateral-Meetings-Web-Scraper

Tasks:
- Work on a paper that analyzes the bilateral meetings between heads of governments and states.
- Specifically, we will download pictures and videos of meetings between leaders (from Google and YouTube)(i), analyze the emotions of leaders from their faces (ii), and check if these emotions are predictive of the future relationship between two countries (iii).

Phase 1:
- Write a scraper that downloads and saves all images that result from a search query. (For example: The search query will be ‘President of United States Barack Obama profile picture’ and the scraper will download and save all images belonging to Barack Obama in a separate folder).
- For each query, download all available pictures (i). Save pictures belonging to individual leaders in separate folders and each folder should be named by the corresponding id of the leader (ii). The name of the folder where you save profile pictures will be countryname_leadername.

Phase 2:
- Using the face_recognition package written for Python, examine the profile pictures you have collected in Phase I, extract the faces from each pictures (i), compare each face to every other face (ii), and identify the faces that match a majority of the other faces in the folder (iii).
- The faces that match with the majority (ideally more than 50%) of the faces in each folder should be designated as the actual profile picture of the leader.

