# Announcements

06/13/2020:  Phase 2 of optional Language Translation now available!  All PGMA-Modernized Indexes now include the ability to translate film/scene summaries from/to alternative languages.  See below for a more detailed explanation.

06/12/2020:  Phase 1 of optional Language Translation now available!  For WayBig, Fagalicious, QueerClick, and IAFD Agents, we now offer optional language translation!   Perhaps you'd prefer not have the movie/scene summary in its native French?  Or, perhaps you'd prefer to get all movie/scene summaries translated to your native German, Korean, or Chinese?  You now have that option for your favorite scenes, and soon you'll soon have these options for all Agents, Agent by Agent. See below for a more detailed explanation.  

06/12/2020:  Local Media Assets now enabled!  See the explanation below for how to take advantage of Local Media Assets below.

06/12/2020:  FAQ Added!  See below.

06/03/2020:  Coming soon!  Each Agent is being updated to offer optional language translation!  

06/01/2020:  The new AEBN Agent is available!  It utilizes the modernized view of AEBN, and offers more metadata functionality (e.g., Exact release dates).  For now, we will support both the new AEBN agent and the legacy AEBNii agent.  However, it is our intent to retire the legacy AEBNii agent.  You won't be required to stop using AEBNii, it will just be removed from the repository and likely no longer supported (e.g., if AEBN makes an update to their site which breaks AEBNii).  

06/06/2020:  The GEVI Agent now allows you to use either the Studio or Distributor name (sometimes they are different) in the **(Studio)** portion of the (Studio) - Title (YYYY).ext naming convention.

05/11/2020 and 05/18/2020:  GayWorld and GayMovie agents were added to the already robust set of Films agents.  While both have limitations in the metadata available, both offer a decent portfolio of movies to match from, and both have superior poster artwork.  

# Plex Metadata Agents for Gay Adult Video
**Please read all this document before usage**

![](https://raw.githubusercontent.com/CodyBerenson/PGMA-Modernized/master/images/preview.gif)
### How to install
1. Clone this repository to your Plex server and copy all of the .bundle folders and their contents to your plugin folder. [Can't find the folder?](https://support.plex.tv/hc/en-us/articles/201106098-How-do-I-find-the-Plug-Ins-folder)
2. Restart your PMS and Login to the web interface and open settings.
3. In Settings > Server > Agents select "Gay Adult" and/or "Gay Adult Films" and/or "Gay Adult Scenes" and check any/all agents you wish to use.
4. Gay Adult contains all of the agents (perhaps for those who commingle Films and Scenes in the same plex library)
5. Gay Adult Films contains specifically the Film agents (e.g., AEBN, GEVI, GayDVDEmpire).  Use in libaries which will mostly or only contain full-length films (see image below)
6. Gay Adult Scenes contains agents for blog sites (WayBig, Fagalicious, QueerClick).  Use in libaries which will mostly or only contain scenes (see image below)
7. In Settings > Server > Agents order the agents by your personal preference (e.g., if most of your movies are found in AEBN, consider putting AEBN first); check Local Media Assets (Movies) if you include your own poster artwork (see below).
8. Create a new library or change the agent of an existing library to the "Gay Adult" or "Gay Adult Scenes" or "Gay Adult Films" agent, then refresh all metadata.

**View the README inside the studio folders to correctly label your files**

### Please Read
**Usage for the Agents:**

**Feature Films:**

(Studio) - Title (Year).ext

e.g.  

(Titan Media) - Copperhead Canyon (2008).mp4

(Raging Stallion Studios) - Manscent (2019).mp4

(Men) - Camp Chaos (2019).mp4

The matching agent will return the movie poster annd relevant metadata,actor thumbnails (matched from IAFD.com) 
![](https://raw.githubusercontent.com/CodyBerenson/PGMA-Modernized/master/images/film.jpg)

**Scenes from blogs:**

(Studio) - Title (Year).ext
e.g., 

(Men Series) - Bellamy Bradley, Alex Fortin, William Seed and Morgan Blake in 'Battle Buddies, Part 4' (2017).mp4

(Active Duty) - Phoenix River and Ryan Jordan (2018).mp4

(Sean Cody) - Jess Tops Deacon (Bareback) (2018).mp4

The matching agent will return a scene poster and relevant metadata,actor thumbnails (matched from IAFD.com) 
![](https://raw.githubusercontent.com/CodyBerenson/PGMA-Modernized/master/images/scene.jpg)



### Gay Erotic Video Index (GEVI) Tips and Considerations:

GEVI has a TREMENDOUS amount of indexed content, but has some quirks that are easy to navigate, if you follow a couple rules, beginning with the filing naming convention (Studio) - Title (Year).ext.  

1.  In GEVI as in the other Agents, if on windows, one cannot use a colon (:) in a filename.  If the site uses a colon either in the Studio or Title replace with space dasy space, i.e. " - ".

2.  When manually searching for a movie, GEVI's results page will display the Company (i.e. Distributor), not the Studio.  The Agent *now* allows you to use either.  Select the movie and click into the movie page.  However, make note of the Title from the Results list.  In this case, the filename should be **(BoyCrush) - Big Uncut Fuckfest, Kyler Moss's (2013).mp4**

![](https://raw.githubusercontent.com/CodyBerenson/PGMA-Modernized/master/images/results.jpg)

![](https://raw.githubusercontent.com/CodyBerenson/PGMA-Modernized/master/images/movie1.jpg)

3.  There are times when the movie page may have multiple line titles (previous and next image).  Use the Title from the Results list.  In this case, the filename should be **(Jake Cruise Media) - Cruise Collection 68 Mike Roberts (2008).mp4**

![](https://raw.githubusercontent.com/CodyBerenson/PGMA-Modernized/master/images/movie2.jpg)

![](https://raw.githubusercontent.com/CodyBerenson/PGMA-Modernized/master/images/results1.jpg)

4.  There are times when the movie page may have one or more AKA titles.  **Use the Title from the Title on the movie page...not the results list as in the previous examples**.  This last example is a good one.  Two movie titles.  Three company names.  A correct filename is **(Pietro Filmes) - Mãos à Obra (2001).mp4** (but remember, you can now use Studio or Distributor)

![](https://raw.githubusercontent.com/CodyBerenson/PGMA-Modernized/master/images/results2.jpg)

![](https://raw.githubusercontent.com/CodyBerenson/PGMA-Modernized/master/images/movie3.jpg)


5. Once you get used to the quirks/workings of the Gay Erotic Video Index site itself, the GEVI is an incredible Plex Agent.  


### Internet Adult Film Database (IAFD) Tips and Considerations:
IAFD is a robust database of adult films and scenes (straight, bi, gay, etc.).  Sometimes, when a particular film can't be found on any of the other indexing sites, or a particular scene can't be found on any of the other blog sites, it will be on IAFD.  We consider it a next-to-last resort (last resort being manually tagging metadata and posters).  However, unlike the other indexes, IAFD contains no posters.  Everyone has their own individual tastes.  To some, the autogenerated poster from Plex may be just fine, as long as the metadata is pulled from IAFD.  For others, metadata isn't enough and a quality poster is needed.  For those whose taste falls into the latter, you have the option of finding a poster that you like for the content, and manually uploading it using Plex's built in functionality (or using Local Media Assets (Movies) (see below).  For example, often on Google you can find studio stills for a particular scene.  If you like one, copy the source URL and upload it manually.  Plex utilizes a 1 x 1.5 ratio for posters (e.g., 600 px width x 900 px height) .  If your image doesn't fit those ratios, Plex will auto crop.  For the connoisseur, you may want to manually adjust in Paint 3d, Photoshop, etc.

For example, the blogs contain very little indexed BlakeMason scene content, whereas IAFD had most, perhaps nearly all, of it (at last for the recent several years).  The IAFD Agent is a good option.

We recommend that you include it last in the order of priority, unless it is your particular go-to agent. 

### Local Media Assets (Movies) Considerations:
This is a useful tool to use, especially in combination with the IAFD Agent.  Suppose there is a film or a scene that can only be found on IAFD.  For example, many Pride Studios and Next Door Studios scenes can't be found on the blogs, but are indexed on IAFD.  Further, those two sites offers high quality photos (not still captures) for that scene, including a 1 x 1.5 ratio image.  If you create a subfolder (e.g., John and James), and put both the IAFD appropriately named scene file *and* the artwork image titled poster.jpg, Plex will grab the metadata for the scene from IAFD and use the poster.jpg image as the poster artwork if Local Media Assets (Movies) is checked in Plex's Agent Settings.   

![](https://raw.githubusercontent.com/CodyBerenson/PGMA-Modernized/master/images/poster3.jpg)

![](https://raw.githubusercontent.com/CodyBerenson/PGMA-Modernized/master/images/poster2.jpg)

![](https://raw.githubusercontent.com/CodyBerenson/PGMA-Modernized/master/images/poster1.jpg)

Another type of local media assets are the tags that may be embedded within a file's properties.  If you'd prefer to use the resulting metadata from one of the blogs vs. what may be encoded in your file's properties, make sure that Local Media Agents is ranked lowest in the ordering of agents. 


### Language Translation

All PGMA-Modernized Agents now provide optional language translation functionality.  Perhaps you're an English speaker and you'd prefer the Summary metadata for your libraries to be in English and not the native French from the index (e.g., https://www.gayeroticvideoindex.com/V/6/49506.html).  Conversely, you'd prefer to have Film and Scene summaries translated to your native German.  Use the translation settings now offered in each Agent.  In most cases, once you make a change to an Agent's Settings, you will need to Stop and then Re-Start your Plex Media Server (PMS) for your changes to take effect.   

![](https://raw.githubusercontent.com/CodyBerenson/PGMA-Modernized/master/images/translation.jpg)
 

### Some final tips:  

1.  Consider using a couple Agents.  Can't find the film you're looking for on AEBN?  Try GEVI. Like the description or poster image better on HomoActive?  Use it.  Remember, that the same film may be on multiple sites, with each site using its specific version of the studio name or title.  Match your filename to the specific site you're wanting to match to. 

2.  The Agent will attempt to crop the scene poster for display in plex, using either an inline cropping service, or if unavailable a visual basic script (for Windows PMS installations).  If both fail, the agent will return the (often oversized) poster as-is from the blog site.  

3.  If you come across a site that indexes films or scenes and has plex style movie covers, it may be a good candidate for a new Agent.  Open an issue and make a request.  **Note: ** we will not create studio specific Agents...studios don't offer plex style movie covers and often update the framework of their site which breaks Agents.

4.  If you have any challenges or struggles, open a new issue.  Please describe your challenge as thoroughly as possible, including which agent you were targeting, the filename and include the log, if you can. **Note:** please, no screenshots that contain graphic content. 


### FAQ:

Q:  When choosing the agent in the library setup window, when it asks for scanner, which scanner option should I choose? Plex Movie Scanner, Plex Video Files, or Plex Video Files Scanner. I'm not sure which one works/works best with this.

A:  Choose Plex Movie Scanner. Then after choosing the plex movie scanner you have three options depending on your library's content:

    For video scenes - use gay adult scenes agent
    For full movies - use gay adult films
    For a mixture - use gay adult


Q:  When setting up the agents for Gay Adult, Gay Adult Scenes and Gay Adult Films the description mentions it utilizes different sources. Are those sources always used or do you need to also manually check the sources you want those agents to use?

A:  For any given set of agents, you choose which sources and the priority that it uses. Let's say that 90% of your content matches from AEBN; certainly choose AEBN and rank it first. 


Q:  I can't get any Scenes to Match on GEVI.  Please help.

A:  The GEVI Agent only scrapes films, not scenes.   Sorry.  


Q:  I can't get the WayBig Agent to match videos.  Help!

A:  The WayBig Agent won't scrape videos from WayBig.com, only Blog entries. If WayBig doesn't have the scene you're seeking, try Fagalicious or QueerClick.  Not on any of the three?  Try IAFD and upload your own poster.


Q:  I've tried everything, and I can't get a particular film/scene to match.  What now?

A:  Open a new Issue.  Please describe the challenge, include the URL for the film/scene, and the corresponding Agent's log file (i.e. if the film is on AEBN, please include the com.plexapp.agents.AEBN.log.) Unsure how to find the log?  This blog entry describes the log location for each PMS platform:  https://support.plex.tv/articles/200250417-plex-media-server-log-files/ The log will be in the PMS Plugin Logs subfolder.   **Please, do not upload graphic images**  Once a new issue is opened, we troubleshoot.  Most root causes turn out to be an incorectly named filename.  However, even though we have robustly tested the agents, we still find anomalies (e.g., special characters) that a particular index may infrequently use which necessitates an update to the logic in the Agent.  If the update is technically feasible, we'll likely make the fix and release the updated Agent.  Regardless of the root cause, you'll be able to track the progress of your issue (and look at any others you may find interesting).  


Q:  I've got a great idea for new functionality...or, there's an indexing site that I use all the time that you haven't provided an agent for.  What should I do?

A:  Open a new Issue.  We love to be challenged with creating new agents or making the current set of agents more robust.  However, we 1) won't create studio specific agents (e.g., SeanCody.com) or 2) likely won't create agents for sites that don't offer consistent quality posterart (IAFD being an obvious exception).  Our goal is to never, or nearly never, have to manually index content.  If you know a site, let us know.  We'll gratefully and happily see if it is feasibly scrapable for Plex metadata.  


Q:  Does the code for the Agents ever change/get updated?

A:  Yes!  We are always developing new agents.  For existing agents, new functionality may be added (e.g., language translation support), or site updates to an index may break the Agent's ability to search.  It is a good practice to periodically check back and install the latest set of code.  Remember to stop and restart your Plex Media Server (PMS) in order for the new/updated Agents to take effect.  


Q:  Any best practices for backing up your Plex libraries and settings? I backup all my video files but wondering if there's another step I should do to make sure my metadata and album artwork is backed up in case of a drive failure. What do you guys do?

A:  There's a topic on the Plex Forum specifically about backing up (and restoring) the PMS libraries and settings: https://support.plex.tv/articles/201539237-backing-up-plex-media-server-data/

Since you're putting so much effort into building awesome libraries, you don't want to take any chances with losing them!


Q:  Why would I want to create separate libraries for movies and scenes?  Why would I want to comingle movies and scenes in one library?

A:  There are pros and cons to each approach. You may want to consider questions such as How many files do you have?  How well-organized is your content?  

Separate libraries:
1.  Pro:  A TimTales library is just that.  You don't have to further filter the library if all you want at that moment is your TimTales content.
2.  Con:  if you click on the actor it only returns matches for that particular library...you'll need to type in the name in the general search engine which will return all libraries;

Combined libaries:
1.  Pro:  One-stop shop.  All your indexed content in one location.
2.  Con:  a downfall of comingling, is that the larger the library grows, the longer Plex takes to scan. 


## Disclaimer


This project stores no images or metadata. All metadata is downloaded directly from publicly-available sources
