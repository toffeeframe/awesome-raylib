# Contribution Guide

The list allows developers to submit their works or any type of media they found in the suitable section, However there are certain rules to adhere by when adding any new content.

For suggesting features and/or improvements, If they aren't done through modifications on the list then an issue could be opened for this.

I took time in writing this guide and willing that it will do the job, My apologies if it doesn't sound perfect at any of ways.

## Content Addition

In order to add content as a contribution, Fork of the repository should be created if no one made before in addition to `git pull` to keep with all recent changes.

1. Fork of the repository should be created if no one made before.
2. `git pull` to always keep the cloned fork with recent changes and additions.
3. The repository uses whitespace indentation and not TABs, Therefore make sure not to modify the file before checking out indentation settings.
4. As a recommendation, Make sure to turn off the "Word Wrap" while editing table content as keeping the option on may cause an annoying view that makes keeping indentation more troublesome.
5. For adding the content the following should be made first if required:

    - Adding account of the developer that own a repository/gist to be added, In case of non-existence:
    
        1. By heading to "Improvements/Suggestions" heading, There is a long list of link reference definitions for developers, It can be seen that it starts with:
            ```md
            <!-- Developers Accounts -->
            ```
        2. The format should use link reference definition in Markdown as `[Developer-Site]` where `Developer` is the developer username (With keeping case sensitivity) and `Site` is where the account exists (eg. GitHub, Codeberg, GitLab, Bitbucket, etc...) lowercased, If no site specific but a `git.` domain then `git` is used.
        3. Make sure the starting of each link in each line is aligned with other ones on same column, Unless if not possible because of new added one is longer then the new indentation for all should be after 2 whitespaces of the colons (:) from the new added definition itself.
    
    - Adding link to the repository, In case of non-existence to add it in a specific section:
        
        1. Below the table that is related to the suitable section, There is a list of link reference definition that can be seen.
        2. The format should use link reference definition in Markdown as `[Developer-RepositoryName]` where `Developer` and `RepositoryName` are the owner (developer username) and name of the repository respectively, With keeping the case sensitivity.
        3. Make sure the starting of each link in each line is aligned with other ones on same column, Unless if not possible because of new added one is longer then the new indentation for all should be after 2 whitespaces of the colons (:) from the new added definition itself.
    
    - Adding link to the gist, In case of non-existence to add it in "Gists" section:
    
        1. Below the table of "Gists" section, There is a list of link reference definitions that can be seen.
        2. The format should use link reference definition in Markdown as `[Developer-GIST_ID]` where `Developer` is the owner (developer username) of the gist (With keeping case sensitivity) and `GIST_ID` is the Gist ID that can be obtained from the final segment of URL.
        3. Make sure the starting of each link in each line is aligned with other ones on same column, Unless if not possible because of new added one is longer then the new indentation for all should be after 2 whitespaces of the colons (:) from the new added definition itself.
    
    - Adding link to the repositories referenced by the repository in the description, In case of mentioned but definition not-existing:
    
        1. By heading to "Improvements/Suggestions" heading, Find the link reference definitions list of "Referenced Repositories" that can be seen starting with:
            ```md
            <!-- Referenced Repositories -->
            ```
        2. Follow the second and third rule of the previous instructions of "Adding link to the repository" as it applies to this section as well.
    
    - Adding link to the site of programming language or library referenced by the repository in the description, In case of mentioned but definition not-existing:
        
        1. By heading to "Improvements/Suggestions" heading, Find the link reference definitions list of "Referenced Sites" that can be seen starting with:
            ```md
            <!-- Referenced Sites (of Libraries, Languages, Articles, etc...) -->
            ```
        2. The format should use link reference definition in Markdown as one of the following:
            
            - `[Language-lang]` which applies for sites of programming langauges, Where `Language` is the programming language name formatted in lowercase and `lang` must be kept as it is.
            - `[NonProgrammingLanguage-site]` which applies for sites of anything that is not classified as programming language, Where `NonProgrammingLanguage` is the software name formatted in lowercase and `site` must be kept as it is.
            - `[Title-wikipedia]` which applies for Wikipedia articles, Where `Title` is the article of the title with case sensitivity being kept as it is and `wikipedia` part should stay as it is.

        3. Make sure the starting of each link in each line is aligned with other ones on same column, Unless if not possible because of new added one is longer then the new indentation for all should be after 2 whitespaces of the colons (:) from the new added definition itself.

    - Adding link to the article(s) author, Only if in case of definition non-existence and the author articles in the "Articles" section are more than one:
        
        1. By heading to "Improvements/Suggestions" heading, Find the link reference definitions list of "Articles Authors" that can be seen starting with:
            ```md
            <!-- Articles Authors -->
            ```
        2. The format should use link reference definition in Markdown as `[Author-Site]` Where `Author` and `Site` are author and site formatted lowercase, Note that if article is hosted over GitHub Pages then addition here fallbacks to rules of adding in "Developers Accounts" instead.
        3. Make sure the starting of each link in each line is aligned with other ones on same column, Unless if not possible because of new added one is longer then the new indentation for all should be after 2 whitespaces of the colons (:) from the new added definition itself.

    - Adding link to the video(s) channel, Only if in case of definition non-existence and the channel videos that will be in the "Videos" and/or "Tutorials" sections are more than one:
    
        1. By heading to "Improvements/Suggestions" heading, Find the link reference definitions list of "Videos Channels" that can be seen starting with:
            ```md
            <!-- Videos Channels (For tutorial and non-tutorial videos) -->
            ```
        2. The format should use link reference definition in Markdown as `[UserID-Site]` where `UserID` is the username or ID of the user (If the site uses case-sensitive IDs then sensitivity must be kept) and `Site` is the site where videos are located formatted in lowercase.
        3. Make sure the starting of each link in each line is aligned with other ones on same column, Unless if not possible because of new added one is longer then the new indentation for all should be after 2 whitespaces of the colons (:) from the new added definition itself.
    
    - Adding new promo images or stickers or logos modelled after the original raylib logo, In case of non-existence in the list to add it:
    
        1. Download the image to add it in the repository (Images in the list must not be loaded from external URL).
        2. Put the image in `logos` folder if it is a logo modelled after the original raylib logo, Or in `promos` folder if it is a promo image or sticker.
        3. Rename image to `projectname` if it is a logo (Add developer username as prefix with dash if multiple names are same for different projects) or to `bannerN` otherwise (Promo Images and Stickers) where `N` is new number that gets incremented after latest image, Regardless of image file format.
    
6. Putting it all, After adding required definitions is done:

    - For the sections where their data are organized in tables (eg. Gists, Softwares, etc...):
    
        1. Head to the section where the new cells containing information would be added to the table, With including required references within formatted text.
        2. Add information cells to each column in a new row, With keeping the rows with separators aligned on same column just fine.
    
    - For the "Articles" section:
    
        - If count of articles by same author is yet just one then:
        
            1. Add inline markdown link with article title and URL leading to the article, In the format:
                ```md
                - [ArticleTitle](ArticleURL)
                ```
            2. After the inline markdown link element immediately, If the article langauge is not in English then the endonym of the content language should be specified into brackets.
        
        - If count of articles by same author is more than one then:
        
            1. Create a nested list in following format:
            
            ```md
            * By [Author][Author-Site]:
                - [ArticleTitle1](ArticleURL1)
                - [ArticleTitle2](ArticleURL2)
                <!-- and so on... -->
            ```
            
            Note that the `Author` inside the first square brackets doesn't follow a formatting rule unlike `[Author-Site]` which follows rules of adding an articles author from the previous step, And each article inside the nested list is added after indentation of 4 spaces.
            
            2. After each element link of each article added in the nested list, If the article langauge is not in English then the endonym of the content language should be specified into brackets.
        
        > If the article is considered a tutorial then it goes into "Tutorials" section instead.
        
    - For the "Tutorials" section:
    
        - If count of tutorials by same creator is yet just one then:
            
            1. Add inline markdown link with tutorial title and URL leading to the tutorial, In the format:
                ```md
                - [TutorialTitle](TutorialURL)
                ```
            2. After the inline markdown link element immediately, If the tutorial langauge is not in English then the endonym of the content language should be specified into brackets.
        
        - If count of tutorials by same creator is more than one then:
        
            1. Create a nested list in following format:
            
            ```md
            * By [TutorialCreator][TutorialCreator-Site]:
                - [TutorialTitle1](TutorialURL1)
                - [TutorialTitle2](TutorialURL2)
                <!-- and so on... -->
            ```
            
            Note that the `TutorialCreator` inside the first square brackets doesn't follow a formatting rule unlike `[TutorialCreator-Site]` which follows rules that is similar to either adding articles author or videos channel of a creator from the previous steps, And each tutorial inside the nested list is added after indentation of 4 spaces.
            
            2. After each element link of each tutorial added in the nested list, If the tutorial langauge is not in English then the endonym of the content language should be specified into brackets.
    
    - For the "Videos" section:
        
        - If count of videos or playlist of videos by same channel is yet just one then:
            
            1. Add inline markdown link with title and URL leading to the video or videos playlist, In the format:
                ```md
                - [VideoOrPlaylistTitle](VideoOrPlaylistURL)
                ```
            2. After the inline markdown link element immediately, If the video or videos playlist langauge is not in English then the endonym of the content language should be specified into brackets.
        
        - If count of videos or playlist of videos by same channel is more than one then:
        
            1. Create a nested list in following format:
            
            ```md
            * By [VideoChannel][VideoChannelUserID-Site]:
                - [VideoOrPlaylistTitle1](VideoOrPlaylistURL1)
                - [VideoOrPlaylistTitle2](VideoOrPlaylistURL2)
                <!-- and so on... -->
            ```
            
            Note that the `VideoChannel` inside the first square brackets doesn't follow a formatting rule unlike `[VideoChannelUserID-Site]` which follows rules of adding videos channel of a creator from the previous steps, And each video or videos playlist inside the nested list is added after indentation of 4 spaces.
            
            2. After each element link of each video or videos playlist added in the nested list, If the video or videos playlist langauge is not in English then the endonym of the content language should be specified into brackets.
            
            > Note that if the playlist does not include a specific video that contains or references raylib then the video should be added separately in another link.
            > If the video is considered a tutorial then it goes into "Tutorials" section instead.
    
    - For both the "Stickers" and "Promo Images" section:
    
        1. Add another list element as inline markdown link with a title that is suitable to the image, With source which is the URL leading to the original source that contains the image.
        2. Add image element below with alternative text that can match the title added from previous step, With link to the image that is downloaded to the suitable folder in the repository to be loaded locally.
        
        > For images that don't have original source link (eg. If from Discord) then basically the added element/item is just title with no linking.

    - For the "Logos" section:
    
        1. Add link reference definition to the repository that contains the logo below the inline images in the list of definitions that can be seen after them, Following same rules of "Adding link to the repository" from previous steps but with addition of title alternative text in format of `"Developer/RepositoryName"` as well.

        2. Add inline image with link for the repository in the format described below, With source which is the URL leading to the original source that contains the image.
            ```md
            [![Developer/RepositoryName](ImageSourceURL)][Developer-RepositoryName]
            ```
            
            > Note that the format for the alternative text in the image uses slash instead of dash.
        
        3. Make sure to keep the starting of links aligned on each row/line in the same column, Which should be made sure of after adding a link to a repository from previous steps.
    
7. `git push` with adding title and description on details of changes.
8. Create a pull request to merge, Note that the pull request will be rejected and not merged if there is a mistake in following the guide.

## Adding to Other Sections

Sections like "Resources and Links" serve as list for official links for raylib and any resources collective that is related, And since the day this list have been made such section like this didn't receive any further changes.

## Adding New Section

If the new section that would be created is arranged in a way that is like other sections then it's not difficult to add with considering to follow guides, But if there is a sense of aware or need for taking opinion on the suggestion of adding the section then it is better to open an issue or make a pull request with prototype or form of the new section to judge if it's suitable to add.
