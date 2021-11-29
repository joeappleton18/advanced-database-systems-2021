# Lecture (Start Here)

<iframe src="https://solent.cloud.panopto.eu/Panopto/Pages/Embed.aspx?id=95329796-b051-4e9f-86ce-adef01651a3e&autoplay=false&offerviewer=true&showtitle=true&showbrand=false&captions=true&interactivity=all" height="405" width="720" style="border: 1px solid #464646;" allowfullscreen allow="autoplay"></iframe>

:::tip sessions dependencies

**Session Dependencies**

This week we are continuing with our wine tasting theme. Please ensure you have the latest version of the project

You can clone this version using the following command:

- `git clone https://github.com/joeappleton18/db-starter-project.git --single-branch --branch week-9-solutions`

This week we will be working in development mode. As such, set up your `.env` file to point to your local MongoDB setup.

**Note**, you might get an error stating "incompatible node environment". This can be fixed by grabbing your version of node, `node -v` then updating the engines property in the `package.json` file to your version of node.
:::

:::tip essential reading

- [MongoDB indexes](https://docs.mongodb.com/manual/indexes/)
- [MongoDB composite text indexes](https://docs.mongodb.com/manual/core/index-text/)

:::

[Last week](/week-9), in deploying our application, concluded our exploration of the fundamental JavaScript technologies needed to create a data-driven web application. This week I want us to consider, for lack of a better term, how we can make our wine application a little less clunky. As such, we will be exploring the following questions:

### How can I introduce front-end JavaScript into my application to allow for database updates without the need for the browser to reload the page?

### How can I take the idea of MongoDB relations further to allow users to favourite wine tastings (a fun little feature)?
