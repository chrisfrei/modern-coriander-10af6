# ✨ modern-coriander ✨

<img src="https://themes.stackbit.com/images/azimuth-demo-1024x768.png" width="600">

This is a [Hugo](https://gohugo.io) site using [Contentful](https://www.contentful.com) as a [CMS](https://en.wikipedia.org/wiki/Content_management_system). It was created with [Stackbit](https://www.stackbit.com?utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes) in under a minute.

You can [create a site](https://app.stackbit.com/create?theme=https://github.com/stackbithq/stackbit-theme-azimuth) just like this one, or explore some variations. How about a different:

<details>
        <summary>🎨 &nbsp;<strong>Look</strong></summary>
        <ul>
                <li><a href="https://app.stackbit.com/create?theme=https://github.com/stackbithq/stackbit-theme-starter&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Ultra customizable starter. A developers&#39; favorite.</a></li>
                <li><a href="https://app.stackbit.com/create?theme=https://github.com/stackbithq/stackbit-theme-exto&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">A portfolio theme with a blog</a></li>
                <li><a href="https://app.stackbit.com/create?theme=https://github.com/stackbithq/stackbit-theme-libris&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">A documentation theme</a></li>
                </ul>
</details>

<details>
        <summary>✏️ &nbsp;<strong>CMS</strong></summary>
        <ul>
                <li><a href="https://app.stackbit.com/create?cms=netlifycms&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Netlify CMS</a></li>
                <li><a href="https://app.stackbit.com/create?cms=sanity&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Sanity</a></li>
                <li><a href="https://app.stackbit.com/create?cms=datocms&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Dato CMS</a></li>
                </ul>
</details>

<details>
        <summary>⚙️ &nbsp;<strong>Static site generator</strong></summary>
        <ul>
                <li><a href="https://app.stackbit.com/create?ssg=gatsby&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Gatsby</a></li>
                <li><a href="https://app.stackbit.com/create?ssg=nextjs&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Next.js</a></li>
                <li><a href="https://app.stackbit.com/create?ssg=jekyll&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Jekyll</a></li>
                </ul>
</details>

## Develop Locally

1. Follow the [installation guide](https://gohugo.io/getting-started/installing/) to install Hugo

1. This theme uses [Hugo Pipes](https://gohugo.io/hugo-pipes/) to handle SCSS – please ensure you have the Hugo extended version installed:

        hugo version

1. Get the project's `stackbit-api-key` from the [Stackbit dashboard](https://app.stackbit.com/dashboard)

1. Assign this key to the `STACKBIT_API_KEY` environment variable (replace `{stackbit_api_key}` with the actual key):

        export STACKBIT_API_KEY={stackbit_api_key}

1. Fetch the content from Contentful:

        npx @stackbit/stackbit-pull --stackbit-pull-api-url=https://api.stackbit.com/pull/5fc10af6aa1c7b0016c6e376

1. Start the Hugo development server:

        hugo server

1. Open [http://localhost:1313/](http://localhost:1313/) in the browser

1. 🎉

## Editing Content

To start editing your site, you can use the Contentful interface at [https://app.contentful.com/spaces/y05sko0iucsb](https://app.contentful.com/spaces/y05sko0iucsb).

Alternatively, you can use the free on-page editing experience provided by the [Stackbit Studio](https://stackbit.com?utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes).

[![](https://i3.ytimg.com/vi/zd9lGRLVDm4/hqdefault.jpg)](https://link.stackbit.com/project-readme-lead-video)

Here's a few resources to get you started:

- 📺 &nbsp; [Editing Content](https://link.stackbit.com/project-readme-editing-video)
- 📺 &nbsp; [Adding, Reordering and Deleting Items](https://link.stackbit.com/project-readme-adding-video)
- 📺 &nbsp; [Collaboration](https://link.stackbit.com/project-readme-collaboration-video)
- 📺 &nbsp; [Publishing](https://link.stackbit.com/project-readme-publishing-video)
- 📚 &nbsp; [Stackbit Documentation](https://www.stackbit.com/docs/)

If you need a hand, make sure to check the [Stackbit support page](https://www.stackbit.com/support?utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes).

## Colophon

Generated at `2020-11-27T15:01:40.612Z` by Stackbit version `0.3.37`.