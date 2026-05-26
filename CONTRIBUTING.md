# Contribution Guide (WIP)

> This guide is still WIP and expected to be done by next commit.

The list allows developers to submit their works or any type of media they found in the suitable section, However there are certain rules to adhere by when adding any new content.

For suggesting features and/or improvements, If they aren't done through modifications on the list then an issue could be opened for this.

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
    
6. Putting it all, After adding required definitions is done:

    - For the sections where their data are organized in tables (eg. Gists, Softwares, etc...):
    
        1. Head to the section where the new cells containing information would be added to the table, With including required references within formatted text.
        2. Add information cells to each column in a new row, With keeping the rows with separators aligned on same column just fine.
    
    - For the "Articles" section:
    
        - If count of articles by the same author are yet just one then:
        
            1. Add inline markdown link with article title and URL leading to the article, In the format:
                ```md
                - [ArticleTitle](ArticleURL)
                ```
            2. After the inline markdown link element immediately, If the article langauge is not in English then the endonym of the content language should be specified into brackets.
        
        - If count of articles by same author are more than one then:
        
            1. Create a nested list in following format:
            
            ```md
            * By [Author][Author-Site]:
                - [ArticleTitle1](ArticleURL1)
                - [ArticleTitle2](ArticleURL2)
                <!-- and so on... -->
            ```
            
            Note that the `Author` inside the first square brackets doesn't follow a formatting rule unlike `[Author-Site]` which follows rules of adding an articles author from the previous step, And each article inside the nested list is added after indentation of 4 spaces.
            
            2. After each element link of each article added in the nested list, If the article langauge is not in English then the endonym of the content language should be specified into brackets.
        
    - For the "Tutorials" section:
    
        1.
        2.
        3.
        4.
    
    - For the "Videos" section:
        
        1.
        2.
        3.
        4.
    
7. `git push` with adding title and description on details of changes.
8. Create a pull request to merge, Note that the pull request will be rejected and not merged if there is a mistake in following the guide.

I took time in writing this guide and willing that it will do the job, My apologizes if it doesn't sound perfect at any of ways.

<!--
TODO add

- "Adding a tutorial"
- "Adding a video" (Include also case of playlists)
- "Adding another logo modified after raylib one"
- "Adding promo images/stickers"
- "Adding to other sections? (that are not mentioned)"
-->

<!--
  - For the sections that include tables (eg. Gists, Softwares, etc...):
    1. Modify and add another table cell(s) containing the project name with its author and description.
    2. Link added information to the links that should added at bottom of table with a new number(s) for them if required (Be careful of number order related to hyperlink when doing so).
  - For the sections that include lists of hyperlink texts (eg. Articles, Tutorials, Videos, etc..):
    1. Modify and add the title of the content with the hyperlink.
    2. If the content language is not in English, Add the language between brackets outside of the hyperlink.
  - For both the Promo Images and Stickers sections:
    1. Add the hyperlink text with the link to the source news or post/tweet where the promo image or sticker comes from.
    2. Add the image below it with the link to it, Note that the image should be downloaded and added to the `promos` folder and not loaded from external source.
  - For the logos of raylib bindings and projects that is modelled after the raylib project logo:
    1. Add the image with hyperlink and alternative text with the same style seen in the markdown, Note that the image should be downloaded and added to the `logos` folder and not loaded from external source.

4. Push and Pull Request, Therefore merge can be done.

Make sure that `git pull` is always done before any additions so no clashes or conflicts would happen before adding and pushing edits on the fork before merging from.
-->