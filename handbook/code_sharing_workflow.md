# Climate CAFE Code-sharing Walkthrough

**_"I am uploading a dataset to Dataverse and would like to share the code I used to generate that dataset. How do I share my code through CAFE?"_**

## Option 1: Dataverse Only
If the code you want to share is relevant only for the specific dataset you are uploading to dataverse, *and* you are not yet comfortable using GitHub and the `git` repository infrastructure, you can simply share your code directly within Dataverse. While we do recommend the use of GitHub for open code sharing, we do not want researchers' comfort level with GitHub to be a barrier code sharing.

To share code directly within Dataverse, simply include your code files alongside the data files when adding your new Dataverse entry (see https://climate-cafe.github.io/tutorial.html).

## Option 2: Personal GitHub, Linked to Dataverse (_recommended_)
If you have your own GitHub account (either a personal or organizational account), you can use GitHub repositories to share your code publicly, and then simply include URL links to connect your GitHub repository and the corresponding Dataverse entry. (Additional tutorials for using GitHub are [coming soon](https://climate-cafe.github.io/github.html)!)

We recommend this method because GitHub offers useful tools for other researchers who want to reproduce or adapt your code in a transparent way. In particular, code developed using GitHub has useful version control documentation built in, and can automatically track the contributions of different team members collaborating on the same code. Once code is shared publicly on GitHub, other users can create "forks" of your repository that enable them to work with your code for their own project, while always showing that the workflow traces back to you, the original author of the code.

If you are sharing your code through a GitHub repository, simply include the URL for the GitHub repository in the description of your corresponding Dataverse entry. For an example, see the metadata section for our example [PM2.5 Components Dataset](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/2NT5CV) on Dataverse, which links to the corresponding reproducible GitHub repository: https://github.com/NSAPH-Data-Processing/pm25_components_randall_martin

Additionally, please include the topic tag `climate-cafe` in your GitHub repository description. This allows anyone to find your repository by searching GitHub for the `climate-cafe` topic keyword. You can easily view all the repositories tagged with `climate-cafe` at https://github.com/topics/climate-cafe. For instructions on how to add a topic tag to a GitHub repository, [click here](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/classifying-your-repository-with-topics).

## Option 3: Personal GitHub, Linked to Dataverse & DM Website
In some cases, your analysis code may be relevant for more than just explaining and reproducing the pipeline for generating your specific dataset. For example, your analysis workflow might offer a useful demonstration of a particular method that other researchers could generalize for their own purposes.

If you anticipate that your shared code could be useful as a walkthrough, or even a kind of tutorial, we can link to your repository from our Climate CAFE Github Organization [landing page](https://climate-cafe.github.io/cafe_github_org.html). This landing page contains links to the current tutorials and code walkthroughs that the CAFE team has developed for researchers to use as resources. Some of those tutorials are associated with particular datasets, but the analyses they demonstrate are intended to stand on their own as general examples. We hope to expand this page to include community-generated tutorials and walkthroughs, so your code could become part of that expansion!

Please contact us if you are interested in having your code linked on the Climate CAFE Github Organization landing page. Note that your code *must* be shared using a GitHub repository to use this option, and you should still plan to link between your GitHub repository and the corresponding Dataverse entry directly as well.

## Option 4: Climate CAFE Organizational GitHub (requires ongoing collaboration)
Finally, if your code is part of a project or demonstration that extends beyond your personal or organizational work, and you would like for it to be published directly under the Climate CAFE organizational title, we can help you share your code through the Climate CAFE Organizational GitHub. This option will require a collaborative worfklow between you and the CAFE Data Management team, including adding you as a contributor to our GitHub organization and managing user permissions. As such, this option is most suitable for collaborators who maintain an active, ongoing role in the Climate CAFE's Community of Practice.
