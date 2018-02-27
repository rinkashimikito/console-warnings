# List of warnings in webdev console

## In views

#### ARTICLE (no SPA)

1. warning.js:33 Warning: Failed prop type: Footer: prop type `children` is invalid; it must be a function, usually from the `prop-types` package, but received `undefined`.

        in Footer (created by Footer)
        in Footer (created by Relay(Footer))
        in Relay(Footer) (created by withRouter(Relay(Footer)))
        in withRouter(Relay(Footer)) (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

2. warning.js:33 Warning: RelayContainer: component `BlogPostLoadedLayout` was rendered with variables that differ from the variables used to fetch fragment `latestVideos`. The fragment was fetched with variables `(not fetched)`, but rendered with variables `{"ids":[21708482,21721883,21727028,21711118,21731346]}`. This can indicate one of two possibilities:
    - The parent set the correct variables in the query - `BlogPostLoadedLayout.getFragment('latestVideos', {...})` - but did not pass the same variables when rendering the component. Be sure to tell the component what variables to use by passing them as props: `<BlogPostLoadedLayout ... ids={...} />`.
    - You are intentionally passing fake data to this component, in which case ignore this warning.

3. warning.js:33 Warning: RelayContainer: component `StoryCollectionComponent` was rendered with variables that differ from the variables used to fetch fragment `latestVideos`. The fragment was fetched with variables `(not fetched)`, but rendered with variables `{}`. This can indicate one of two possibilities:
    - The parent set the correct variables in the query - `StoryCollectionComponent.getFragment('latestVideos', {...})` - but did not pass the same variables when rendering the component. Be sure to tell the component what variables to use by passing them as props: `<StoryCollectionComponent ...  />`.
    - You are intentionally passing fake data to this component, in which case ignore this warning.

#### ARTICLE (SPA)

1. warning.js:33 Warning: RelayContainer: Expected prop `storyCollection` to be supplied to `UniversalComponent`, but got `undefined`. Pass an explicit `null` if this is intentional.

2. warning.js:33 Warning: RelayContainer: Expected prop `latestUpdates` to be supplied to `UniversalComponent`, but got `undefined`. Pass an explicit `null` if this is intentional.

3. warning.js:33 Warning: RelayContainer: Expected prop `relatedStoryCollection` to be supplied to `UniversalComponent`, but got `undefined`. Pass an explicit `null` if this is intentional.

4. warning.js:33 Warning: RelayContainer: Expected prop `latestVideos` to be supplied to `UniversalComponent`, but got `undefined`. Pass an explicit `null` if this is intentional.

5. warning.js:33 Warning: Failed prop type: The prop `blogPost.commentCount` is marked as required in `BlogPostLayout`, but its value is `undefined`.

        in BlogPostLayout (created by BlogPostOptimistic)
        in BlogPostOptimistic (created by I13nBlogPostOptimistic)
        in I13nBlogPostOptimistic (created by ContentMapperLayout)
        in ContentMapperLayout (created by UniversalComponent)
        in UniversalComponent (created by Relay(UniversalComponent))
        in Relay(UniversalComponent) (created by Connect(Relay(UniversalComponent)))
        in Connect(Relay(UniversalComponent)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in main (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

6. warning.js:33 Warning: RelayContainer: component `BlogPostIdentityLayout` was rendered with variables that differ from the variables used to fetch fragment `parent`. The fragment was fetched with variables `(not fetched)`, but rendered with variables `{}`. This can indicate one of two possibilities:
    - The parent set the correct variables in the query - `BlogPostIdentityLayout.getFragment('parent', {...})` - but did not pass the same variables when rendering the component. Be sure to tell the component what variables to use by passing them as props: `<BlogPostIdentityLayout ...  />`.
    - You are intentionally passing fake data to this component, in which case ignore this warning.

7. warning.js:33 Warning: Failed prop type: The prop `commentCount` is marked as required in `BlogPostLayout`, but its value is `undefined`.

        in BlogPostLayout (created by Connect(BlogPostLayout))
        in Connect(BlogPostLayout) (created by I13nConnect(BlogPostLayout))
        in I13nConnect(BlogPostLayout) (created by BlogPostLayout)
        in div (created by MainContentLayout)
        in div (created by MainContentLayout)
        in MainContentLayout (created by Connect(MainContentLayout))
        in Connect(MainContentLayout) (created by BlogPostLayout)
        in div (created by BlogPostLayout)
        in BlogPostLayout (created by BlogPostOptimistic)
        in BlogPostOptimistic (created by I13nBlogPostOptimistic)
        in I13nBlogPostOptimistic (created by ContentMapperLayout)
        in ContentMapperLayout (created by UniversalComponent)
        in UniversalComponent (created by Relay(UniversalComponent))
        in Relay(UniversalComponent) (created by Connect(Relay(UniversalComponent)))
        in Connect(Relay(UniversalComponent)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in main (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

8. warning.js:33 Warning: Failed prop type: The prop `commentStatus` is marked as required in `BlogPostLayout`, but its value is `undefined`.

        in BlogPostLayout (created by Connect(BlogPostLayout))
        in Connect(BlogPostLayout) (created by I13nConnect(BlogPostLayout))
        in I13nConnect(BlogPostLayout) (created by BlogPostLayout)
        in div (created by MainContentLayout)
        in div (created by MainContentLayout)
        in MainContentLayout (created by Connect(MainContentLayout))
        in Connect(MainContentLayout) (created by BlogPostLayout)
        in div (created by BlogPostLayout)
        in BlogPostLayout (created by BlogPostOptimistic)
        in BlogPostOptimistic (created by I13nBlogPostOptimistic)
        in I13nBlogPostOptimistic (created by ContentMapperLayout)
        in ContentMapperLayout (created by UniversalComponent)
        in UniversalComponent (created by Relay(UniversalComponent))
        in Relay(UniversalComponent) (created by Connect(Relay(UniversalComponent)))
        in Connect(Relay(UniversalComponent)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in main (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

9. warning.js:33 Warning: Cannot update during an existing state transition (such as within `render` or another component's constructor). Render methods should be a pure function of props and state; constructor side-effects are an anti-pattern, but can be moved to `componentWillMount`.

10. warning.js:33 Warning: RelayContainer: component `StoryCollectionComponent` was rendered with variables that differ from the variables used to fetch fragment `latestVideos`. The fragment was fetched with variables `(not fetched)`, but rendered with variables `{}`. This can indicate one of two possibilities:
    - The parent set the correct variables in the query - `StoryCollectionComponent.getFragment('latestVideos', {...})` - but did not pass the same variables when rendering the component. Be sure to tell the component what variables to use by passing them as props: `<StoryCollectionComponent ...  />`.
    - You are intentionally passing fake data to this component, in which case ignore this warning.

11. warning.js:33 Warning: RelayContainer: component `BlogPostLoadedLayout` was rendered with variables that differ from the variables used to fetch fragment `latestVideos`. The fragment was fetched with variables `(not fetched)`, but rendered with variables `{"ids":[21708482,21721883,21727028,21711118,21731346]}`. This can indicate one of two possibilities:
    - The parent set the correct variables in the query - `BlogPostLoadedLayout.getFragment('latestVideos', {...})` - but did not pass the same variables when rendering the component. Be sure to tell the component what variables to use by passing them as props: `<BlogPostLoadedLayout ... ids={...} />`.
    - You are intentionally passing fake data to this component, in which case ignore this warning.

#### GRAPHIC DETAILS (no SPA)

1. warning.js:33 Warning: Received `false` for a non-boolean attribute `rel`.
If you want to write it to the DOM, pass a string instead: rel="false" or rel={value.toString()}.
If you used to conditionally omit it with rel={condition && value}, pass rel={condition ? value : undefined} instead.

        in a (created by Link)
        in Link (created by Link)
        in Link (created by TeaserListLayout)
        in li (created by TeaserListLayout)
        in ul (created by TeaserListLayout)
        in div (created by TeaserListLayout)
        in div (created by TeaserListLayout)
        in div (created by MainContentLayout)
        in MainContentLayout (created by Connect(MainContentLayout))
        in Connect(MainContentLayout) (created by TeaserListLayout)
        in div (created by MainContentLayout)
        in div (created by MainContentLayout)
        in MainContentLayout (created by Connect(MainContentLayout))
        in Connect(MainContentLayout) (created by TeaserListLayout)
        in div (created by TeaserListLayout)
        in TeaserListLayout (created by Relay(TeaserListLayout))
        in Relay(TeaserListLayout) (created by TeaserListOptimistic)
        in TeaserListOptimistic (created by ContentMapperLayout)
        in ContentMapperLayout (created by UniversalComponent)
        in UniversalComponent (created by Relay(UniversalComponent))
        in Relay(UniversalComponent) (created by Connect(Relay(UniversalComponent)))
        in Connect(Relay(UniversalComponent)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in main (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

2. warning.js:33 Warning: Failed prop type: Footer: prop type `children` is invalid; it must be a function, usually from the `prop-types` package, but received `undefined`.

        in Footer (created by Footer)
        in Footer (created by Relay(Footer))
        in Relay(Footer) (created by withRouter(Relay(Footer)))
        in withRouter(Relay(Footer)) (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

#### GRAPHIC DETAILS (SPA)

1. warning.js:33 Warning: RelayContainer: Expected prop `storyCollection` to be supplied to `UniversalComponent`, but got `undefined`. Pass an explicit `null` if this is intentional.

2. warning.js:33 Warning: RelayContainer: Expected prop `latestUpdates` to be supplied to `UniversalComponent`, but got `undefined`. Pass an explicit `null` if this is intentional.

3. warning.js:33 Warning: RelayContainer: Expected prop `relatedStoryCollection` to be supplied to `UniversalComponent`, but got `undefined`. Pass an explicit `null` if this is intentional.

4. warning.js:33 Warning: RelayContainer: Expected prop `latestVideos` to be supplied to `UniversalComponent`, but got `undefined`. Pass an explicit `null` if this is intentional.

5. warning.js:33 Warning: Failed prop type: The prop `location` is marked as required in `ContentMapperLayout`, but its value is `undefined`.

        in ContentMapperLayout (created by UniversalComponent)
        in UniversalComponent (created by Relay(UniversalComponent))
        in Relay(UniversalComponent) (created by Connect(Relay(UniversalComponent)))
        in Connect(Relay(UniversalComponent)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in main (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

6. warning.js:33 Warning: RelayContainer: component `HeaderLayout` was rendered with variables that differ from the variables used to fetch fragment `blog`. The fragment was fetched with variables `(not fetched)`, but rendered with variables `{}`. This can indicate one of two possibilities:
    - The parent set the correct variables in the query - `HeaderLayout.getFragment('blog', {...})` - but did not pass the same variables when rendering the component. Be sure to tell the component what variables to use by passing them as props: `<HeaderLayout ...  />`.
    - You are intentionally passing fake data to this component, in which case ignore this warning.

7. warning.js:33 Warning: Failed prop type: Invalid prop `children` supplied to `MainContentLayout`, expected a ReactNode.

        in MainContentLayout (created by Connect(MainContentLayout))
        in Connect(MainContentLayout) (created by TeaserListLayout)
        in div (created by TeaserListLayout)
        in TeaserListLayout (created by TeaserListOptimistic)
        in TeaserListOptimistic (created by ContentMapperLayout)
        in ContentMapperLayout (created by UniversalComponent)
        in UniversalComponent (created by Relay(UniversalComponent))
        in Relay(UniversalComponent) (created by Connect(Relay(UniversalComponent)))
        in Connect(Relay(UniversalComponent)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in main (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

8. warning.js:33 Warning: RelayContainer: component `TeaserLayout` was rendered with variables that differ from the variables used to fetch fragment `blogPost`. The fragment was fetched with variables `(not fetched)`, but rendered with variables `{}`. This can indicate one of two possibilities:
    - The parent set the correct variables in the query - `TeaserLayout.getFragment('blogPost', {...})` - but did not pass the same variables when rendering the component. Be sure to tell the component what variables to use by passing them as props: `<TeaserLayout ...  />`.
    - You are intentionally passing fake data to this component, in which case ignore this warning.

9. warning.js:33 Warning: Received `false` for a non-boolean attribute `rel`.
If you want to write it to the DOM, pass a string instead: rel="false" or rel={value.toString()}.
If you used to conditionally omit it with rel={condition && value}, pass rel={condition ? value : undefined} instead.

        in a (created by Link)
        in Link (created by Link)
        in Link (created by TeaserListLayout)
        in li (created by TeaserListLayout)
        in ul (created by TeaserListLayout)
        in div (created by TeaserListLayout)
        in div (created by TeaserListLayout)
        in div (created by MainContentLayout)
        in MainContentLayout (created by Connect(MainContentLayout))
        in Connect(MainContentLayout) (created by TeaserListLayout)
        in div (created by MainContentLayout)
        in div (created by MainContentLayout)
        in MainContentLayout (created by Connect(MainContentLayout))
        in Connect(MainContentLayout) (created by TeaserListLayout)
        in div (created by TeaserListLayout)
        in TeaserListLayout (created by Relay(TeaserListLayout))
        in Relay(TeaserListLayout) (created by TeaserListOptimistic)
        in TeaserListOptimistic (created by ContentMapperLayout)
        in ContentMapperLayout (created by UniversalComponent)
        in UniversalComponent (created by Relay(UniversalComponent))
        in Relay(UniversalComponent) (created by Connect(Relay(UniversalComponent)))
        in Connect(Relay(UniversalComponent)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in main (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

#### HOMEPAGE

1. warning.js:33 Warning: RelayContainer: component `StoryCollectionComponent` was rendered with variables that differ from the variables used to fetch fragment `blog`. The fragment was fetched with variables `(not fetched)`, but rendered with variables `{}`. This can indicate one of two possibilities:
    - The parent set the correct variables in the query - `StoryCollectionComponent.getFragment('blog', {...})` - but did not pass the same variables when rendering the component. Be sure to tell the component what variables to use by passing them as props: `<StoryCollectionComponent ...  />`.
    - You are intentionally passing fake data to this component, in which case ignore this warning.

2. warning.js:33 Warning: validateDOMNesting(...): \<a> cannot appear as a descendant of \<a>.

        in a (created by TeaserLayout)
        in div (created by TeaserLayout)
        in div (created by TeaserLayout)
        in a (created by I13na)
        in I13na (created by Link)
        in Link (created by OptimisticLink)
        in OptimisticLink (created by TeaserLayout)
        in article (created by Teaser)
        in Teaser (created by TeaserLayout)
        in TeaserLayout (created by Relay(TeaserLayout))
        in Relay(TeaserLayout) (created by StoryCollectionComponent)
        in div (created by StoryCollectionComponent)
        in StoryCollectionComponent (created by Relay(StoryCollectionComponent))
        in Relay(StoryCollectionComponent) (created by HomePageLayout)
        in div (created by I13ndiv)
        in I13ndiv (created by HomePageLayout)
        in HomePageLayout (created by UniversalComponent)
        in UniversalComponent (created by Relay(UniversalComponent))
        in Relay(UniversalComponent) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in main (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

3. warning.js:33 Warning: Failed prop type: Footer: prop type `children` is invalid; it must be a function, usually from the `prop-types` package, but received `undefined`.

        in Footer (created by Footer)
        in Footer (created by Relay(Footer))
        in Relay(Footer) (created by withRouter(Relay(Footer)))
        in withRouter(Relay(Footer)) (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

#### LATEST UPDATES (SPA)

1. warning.js:33 Warning: RelayContainer: component `UniversalComponent` was rendered with variables that differ from the variables used to fetch fragment `mapper`. The fragment was fetched with variables `(not fetched)`, but rendered with variables `{"page":0,"collectionID":21708482}`. This can indicate one of two possibilities:
    - The parent set the correct variables in the query - `UniversalComponent.getFragment('mapper', {...})` - but did not pass the same variables when rendering the component. Be sure to tell the component what variables to use by passing them as props: `<UniversalComponent ... page={...} collectionID={...} />`.
    - You are intentionally passing fake data to this component, in which case ignore this warning.

2. warning.js:33 Warning: Failed prop type: The prop `location` is marked as required in `ContentMapperLayout`, but its value is `undefined`.

        in ContentMapperLayout (created by UniversalComponent)
        in UniversalComponent (created by Relay(UniversalComponent))
        in Relay(UniversalComponent) (created by Connect(Relay(UniversalComponent)))
        in Connect(Relay(UniversalComponent)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in main (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

3. warning.js:33 Warning: RelayContainer: component `HeaderLayout` was rendered with variables that differ from the variables used to fetch fragment `blog`. The fragment was fetched with variables `(not fetched)`, but rendered with variables `{}`. This can indicate one of two possibilities:
    - The parent set the correct variables in the query - `HeaderLayout.getFragment('blog', {...})` - but did not pass the same variables when rendering the component. Be sure to tell the component what variables to use by passing them as props: `<HeaderLayout ...  />`.
    - You are intentionally passing fake data to this component, in which case ignore this warning.

4. warning.js:33 Warning: Failed prop type: Invalid prop `children` supplied to `MainContentLayout`, expected a ReactNode.

        in MainContentLayout (created by Connect(MainContentLayout))
        in Connect(MainContentLayout) (created by TeaserListLayout)
        in div (created by TeaserListLayout)
        in TeaserListLayout (created by TeaserListOptimistic)
        in TeaserListOptimistic (created by ContentMapperLayout)
        in ContentMapperLayout (created by UniversalComponent)
        in UniversalComponent (created by Relay(UniversalComponent))
        in Relay(UniversalComponent) (created by Connect(Relay(UniversalComponent)))
        in Connect(Relay(UniversalComponent)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in main (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

5. warning.js:33 Warning: RelayContainer: component `TeaserLayout` was rendered with variables that differ from the variables used to fetch fragment `blogPost`. The fragment was fetched with variables `(not fetched)`, but rendered with variables `{}`. This can indicate one of two possibilities:
    - The parent set the correct variables in the query - `TeaserLayout.getFragment('blogPost', {...})` - but did not pass the same variables when rendering the component. Be sure to tell the component what variables to use by passing them as props: `<TeaserLayout ...  />`.
    - You are intentionally passing fake data to this component, in which case ignore this warning.

6. warning.js:33 Warning: RelayContainer: Expected prop `storyCollection` to be supplied to `UniversalComponent`, but got `undefined`. Pass an explicit `null` if this is intentional.

7. warning.js:33 Warning: RelayContainer: Expected prop `latestUpdates` to be supplied to `UniversalComponent`, but got `undefined`. Pass an explicit `null` if this is intentional.

8. warning.js:33 Warning: RelayContainer: Expected prop `relatedStoryCollection` to be supplied to `UniversalComponent`, but got `undefined`. Pass an explicit `null` if this is intentional.

9. warning.js:33 Warning: RelayContainer: Expected prop `latestVideos` to be supplied to `UniversalComponent`, but got `undefined`. Pass an explicit `null` if this is intentional.

#### LATEST UPDATES (no SPA)

1. warning.js:33 Warning: Failed prop type: Footer: prop type `children` is invalid; it must be a function, usually from the `prop-types` package, but received `undefined`.

        in Footer (created by Footer)
        in Footer (created by Relay(Footer))
        in Relay(Footer) (created by withRouter(Relay(Footer)))
        in withRouter(Relay(Footer)) (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

#### PRINT EDITION (SPA)

1. warning.js:33 Warning: RelayContainer: component `UniversalComponent` was rendered with variables that differ from the variables used to fetch fragment `mapper`. The fragment was fetched with variables `(not fetched)`, but rendered with variables `{"page":0,"collectionID":21708482}`. This can indicate one of two possibilities:
    - The parent set the correct variables in the query - `UniversalComponent.getFragment('mapper', {...})` - but did not pass the same variables when rendering the component. Be sure to tell the component what variables to use by passing them as props: `<UniversalComponent ... page={...} collectionID={...} />`.
    - You are intentionally passing fake data to this component, in which case ignore this warning.

2. warning.js:33 Warning: Failed prop type: The prop `location` is marked as required in `ContentMapperLayout`, but its value is `undefined`.

        in ContentMapperLayout (created by UniversalComponent)
        in UniversalComponent (created by Relay(UniversalComponent))
        in Relay(UniversalComponent) (created by Connect(Relay(UniversalComponent)))
        in Connect(Relay(UniversalComponent)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in main (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

3. warning.js:33 Warning: Failed prop type: The prop `pageInformationStore` is marked as required in `PrintEditionLayout`, but its value is `undefined`.

        in PrintEditionLayout (created by PrintEditionOptimistic)
        in PrintEditionOptimistic (created by ContentMapperLayout)
        in ContentMapperLayout (created by UniversalComponent)
        in UniversalComponent (created by Relay(UniversalComponent))
        in Relay(UniversalComponent) (created by Connect(Relay(UniversalComponent)))
        in Connect(Relay(UniversalComponent)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in main (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

4. warning.js:33 Warning: RelayContainer: Expected prop `storyCollection` to be supplied to `UniversalComponent`, but got `undefined`. Pass an explicit `null` if this is intentional.

5. warning.js:33 Warning: RelayContainer: Expected prop `latestUpdates` to be supplied to `UniversalComponent`, but got `undefined`. Pass an explicit `null` if this is intentional.

6. warning.js:33 Warning: RelayContainer: Expected prop `relatedStoryCollection` to be supplied to `UniversalComponent`, but got `undefined`. Pass an explicit `null` if this is intentional.

7. warning.js:33 Warning: RelayContainer: Expected prop `latestVideos` to be supplied to `UniversalComponent`, but got `undefined`. Pass an explicit `null` if this is intentional.

8. warning.js:33 Warning: RelayContainer: component `PrintEditionLayout` was rendered with variables that differ from the variables used to fetch fragment `storyCollection`. The fragment was fetched with variables `(not fetched)`, but rendered with variables `{}`. This can indicate one of two possibilities:
    - The parent set the correct variables in the query - `PrintEditionLayout.getFragment('storyCollection', {...})` - but did not pass the same variables when rendering the component. Be sure to tell the component what variables to use by passing them as props: `<PrintEditionLayout ...  />`.
    - You are intentionally passing fake data to this component, in which case ignore this warning.

#### PRINT EDITION (no SPA)

1. warning.js:33 Warning: RelayContainer: component `PrintEditionLayout` was rendered with variables that differ from the variables used to fetch fragment `storyCollection`. The fragment was fetched with variables `(not fetched)`, but rendered with variables `{}`. This can indicate one of two possibilities:
    - The parent set the correct variables in the query - `PrintEditionLayout.getFragment('storyCollection', {...})` - but did not pass the same variables when rendering the component. Be sure to tell the component what variables to use by passing them as props: `<PrintEditionLayout ...  />`.
    - You are intentionally passing fake data to this component, in which case ignore this warning.

2. warning.js:33 Warning: Failed prop type: Footer: prop type `children` is invalid; it must be a function, usually from the `prop-types` package, but received `undefined`.

        in Footer (created by Footer)
        in Footer (created by Relay(Footer))
        in Relay(Footer) (created by withRouter(Relay(Footer)))
        in withRouter(Relay(Footer)) (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

#### SIGNUP PAGE (SPA)

1. warning.js:33 Warning: Failed prop type: Footer: prop type `children` is invalid; it must be a function, usually from the `prop-types` package, but received `undefined`.

        in Footer (created by Footer)
        in Footer (created by Relay(Footer))
        in Relay(Footer) (created by withRouter(Relay(Footer)))
        in withRouter(Relay(Footer)) (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

2. free-email-newsletter-signup?destination=%2Fnews%2Fmiddle-east-and-africa%2F21737335-former-aide-may-spill-beans-prime-minister-pressure-binyamin:1 [DOM] Found 2 elements with non-unique id #user-login: (More info: https://goo.gl/9p2vKq) <form action=​"https:​/​/​stage.economist.com/​user/​login?destination=%2Ffree-email-newsletter-signup" accept-charset=​"UTF-8" method=​"post" id=​"user-login" class=​"user-menu-login-form">​…​</form>​ <form action=​"https:​/​/​stage.economist.com/​user/​login?destination=/​newsletters" accept-charset=​"UTF-8" method=​"post" id=​"user-login" class=​"user-menu-login-form">​…​</form>​

#### SIGNUP PAGE (no SPA)

1. warning.js:33 Warning: Failed prop type: Footer: prop type `children` is invalid; it must be a function, usually from the `prop-types` package, but received `undefined`.

        in Footer (created by Footer)
        in Footer (created by Relay(Footer))
        in Relay(Footer) (created by withRouter(Relay(Footer)))
        in withRouter(Relay(Footer)) (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication


2. free-email-newsletter-signup?destination=%2Fnews%2Fmiddle-east-and-africa%2F21737335-former-aide-may-spill-beans-prime-minister-pressure-binyamin:1 [DOM] Found 2 elements with non-unique id #user-login: (More info: https://goo.gl/9p2vKq) <form action=​"https:​/​/​stage.economist.com/​user/​login?destination=%2Ffree-email-newsletter-signup" accept-charset=​"UTF-8" method=​"post" id=​"user-login" class=​"user-menu-login-form">​…​</form>​ <form action=​"https:​/​/​stage.economist.com/​user/​login?destination=/​newsletters" accept-charset=​"UTF-8" method=​"post" id=​"user-login" class=​"user-menu-login-form">​…​</form>​

#### SIGNUP PAGE (Search button click)

1. warning.js:33 Warning: React does not recognize the `buttonRole` prop on a DOM element. If you intentionally want it to appear in the DOM as a custom attribute, spell it as lowercase `buttonrole` instead. If you accidentally passed it from a parent component, remove it from the DOM element.

        in a (created by Link)
        in Link (created by Button)
        in Button (created by NavigationLayout)
        in div (created by NavigationLayout)
        in div (created by NavigationLayout)
        in div (created by NavigationLayout)
        in div (created by NavigationLayout)
        in NavigationLayout (created by Relay(NavigationLayout))
        in Relay(NavigationLayout) (created by Connect(Relay(NavigationLayout)))
        in Connect(Relay(NavigationLayout)) (created by I13nConnect(Relay(NavigationLayout)))
        in I13nConnect(Relay(NavigationLayout)) (created by MainLayout)
        in div (created by StickyScroller)
        in StickyScroller (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

## Unique warnings

1. warning.js:33 Warning: Failed prop type: Footer: prop type `children` is invalid; it must be a function, usually from the `prop-types` package, but received `undefined`.

        in Footer (created by Footer)
        in Footer (created by Relay(Footer))
        in Relay(Footer) (created by withRouter(Relay(Footer)))
        in withRouter(Relay(Footer)) (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

2. warning.js:33 Warning: RelayContainer: component `BlogPostLoadedLayout` was rendered with variables that differ from the variables used to fetch fragment `latestVideos`. The fragment was fetched with variables `(not fetched)`, but rendered with variables `{"ids":[21708482,21721883,21727028,21711118,21731346]}`. This can indicate one of two possibilities:
    - The parent set the correct variables in the query - `BlogPostLoadedLayout.getFragment('latestVideos', {...})` - but did not pass the same variables when rendering the component. Be sure to tell the component what variables to use by passing them as props: `<BlogPostLoadedLayout ... ids={...} />`.
    - You are intentionally passing fake data to this component, in which case ignore this warning.

3. warning.js:33 Warning: RelayContainer: component `StoryCollectionComponent` was rendered with variables that differ from the variables used to fetch fragment `latestVideos`. The fragment was fetched with variables `(not fetched)`, but rendered with variables `{}`. This can indicate one of two possibilities:
    - The parent set the correct variables in the query - `StoryCollectionComponent.getFragment('latestVideos', {...})` - but did not pass the same variables when rendering the component. Be sure to tell the component what variables to use by passing them as props: `<StoryCollectionComponent ...  />`.
    - You are intentionally passing fake data to this component, in which case ignore this warning.

4. warning.js:33 Warning: RelayContainer: Expected prop `storyCollection` to be supplied to `UniversalComponent`, but got `undefined`. Pass an explicit `null` if this is intentional.

5. warning.js:33 Warning: RelayContainer: Expected prop `latestUpdates` to be supplied to `UniversalComponent`, but got `undefined`. Pass an explicit `null` if this is intentional.

6. warning.js:33 Warning: RelayContainer: Expected prop `relatedStoryCollection` to be supplied to `UniversalComponent`, but got `undefined`. Pass an explicit `null` if this is intentional.

7. warning.js:33 Warning: RelayContainer: Expected prop `latestVideos` to be supplied to `UniversalComponent`, but got `undefined`. Pass an explicit `null` if this is intentional.

8. warning.js:33 Warning: Failed prop type: The prop `blogPost.commentCount` is marked as required in `BlogPostLayout`, but its value is `undefined`.

        in BlogPostLayout (created by BlogPostOptimistic)
        in BlogPostOptimistic (created by I13nBlogPostOptimistic)
        in I13nBlogPostOptimistic (created by ContentMapperLayout)
        in ContentMapperLayout (created by UniversalComponent)
        in UniversalComponent (created by Relay(UniversalComponent))
        in Relay(UniversalComponent) (created by Connect(Relay(UniversalComponent)))
        in Connect(Relay(UniversalComponent)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in main (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

9. warning.js:33 Warning: RelayContainer: component `BlogPostIdentityLayout` was rendered with variables that differ from the variables used to fetch fragment `parent`. The fragment was fetched with variables `(not fetched)`, but rendered with variables `{}`. This can indicate one of two possibilities:
    - The parent set the correct variables in the query - `BlogPostIdentityLayout.getFragment('parent', {...})` - but did not pass the same variables when rendering the component. Be sure to tell the component what variables to use by passing them as props: `<BlogPostIdentityLayout ...  />`.
    - You are intentionally passing fake data to this component, in which case ignore this warning.

10. warning.js:33 Warning: Failed prop type: The prop `commentCount` is marked as required in `BlogPostLayout`, but its value is `undefined`.

        in BlogPostLayout (created by Connect(BlogPostLayout))
        in Connect(BlogPostLayout) (created by I13nConnect(BlogPostLayout))
        in I13nConnect(BlogPostLayout) (created by BlogPostLayout)
        in div (created by MainContentLayout)
        in div (created by MainContentLayout)
        in MainContentLayout (created by Connect(MainContentLayout))
        in Connect(MainContentLayout) (created by BlogPostLayout)
        in div (created by BlogPostLayout)
        in BlogPostLayout (created by BlogPostOptimistic)
        in BlogPostOptimistic (created by I13nBlogPostOptimistic)
        in I13nBlogPostOptimistic (created by ContentMapperLayout)
        in ContentMapperLayout (created by UniversalComponent)
        in UniversalComponent (created by Relay(UniversalComponent))
        in Relay(UniversalComponent) (created by Connect(Relay(UniversalComponent)))
        in Connect(Relay(UniversalComponent)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in main (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

11. warning.js:33 Warning: Failed prop type: The prop `commentStatus` is marked as required in `BlogPostLayout`, but its value is `undefined`.

        in BlogPostLayout (created by Connect(BlogPostLayout))
        in Connect(BlogPostLayout) (created by I13nConnect(BlogPostLayout))
        in I13nConnect(BlogPostLayout) (created by BlogPostLayout)
        in div (created by MainContentLayout)
        in div (created by MainContentLayout)
        in MainContentLayout (created by Connect(MainContentLayout))
        in Connect(MainContentLayout) (created by BlogPostLayout)
        in div (created by BlogPostLayout)
        in BlogPostLayout (created by BlogPostOptimistic)
        in BlogPostOptimistic (created by I13nBlogPostOptimistic)
        in I13nBlogPostOptimistic (created by ContentMapperLayout)
        in ContentMapperLayout (created by UniversalComponent)
        in UniversalComponent (created by Relay(UniversalComponent))
        in Relay(UniversalComponent) (created by Connect(Relay(UniversalComponent)))
        in Connect(Relay(UniversalComponent)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in main (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

12. warning.js:33 Warning: Cannot update during an existing state transition (such as within `render` or another component's constructor). Render methods should be a pure function of props and state; constructor side-effects are an anti-pattern, but can be moved to `componentWillMount`.

13. warning.js:33 Warning: Received `false` for a non-boolean attribute `rel`.
If you want to write it to the DOM, pass a string instead: rel="false" or rel={value.toString()}.
If you used to conditionally omit it with rel={condition && value}, pass rel={condition ? value : undefined} instead.

        in a (created by Link)
        in Link (created by Link)
        in Link (created by TeaserListLayout)
        in li (created by TeaserListLayout)
        in ul (created by TeaserListLayout)
        in div (created by TeaserListLayout)
        in div (created by TeaserListLayout)
        in div (created by MainContentLayout)
        in MainContentLayout (created by Connect(MainContentLayout))
        in Connect(MainContentLayout) (created by TeaserListLayout)
        in div (created by MainContentLayout)
        in div (created by MainContentLayout)
        in MainContentLayout (created by Connect(MainContentLayout))
        in Connect(MainContentLayout) (created by TeaserListLayout)
        in div (created by TeaserListLayout)
        in TeaserListLayout (created by Relay(TeaserListLayout))
        in Relay(TeaserListLayout) (created by TeaserListOptimistic)
        in TeaserListOptimistic (created by ContentMapperLayout)
        in ContentMapperLayout (created by UniversalComponent)
        in UniversalComponent (created by Relay(UniversalComponent))
        in Relay(UniversalComponent) (created by Connect(Relay(UniversalComponent)))
        in Connect(Relay(UniversalComponent)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in main (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

14. warning.js:33 Warning: Failed prop type: The prop `location` is marked as required in `ContentMapperLayout`, but its value is `undefined`.

        in ContentMapperLayout (created by UniversalComponent)
        in UniversalComponent (created by Relay(UniversalComponent))
        in Relay(UniversalComponent) (created by Connect(Relay(UniversalComponent)))
        in Connect(Relay(UniversalComponent)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in main (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

15. warning.js:33 Warning: RelayContainer: component `HeaderLayout` was rendered with variables that differ from the variables used to fetch fragment `blog`. The fragment was fetched with variables `(not fetched)`, but rendered with variables `{}`. This can indicate one of two possibilities:
    - The parent set the correct variables in the query - `HeaderLayout.getFragment('blog', {...})` - but did not pass the same variables when rendering the component. Be sure to tell the component what variables to use by passing them as props: `<HeaderLayout ...  />`.
    - You are intentionally passing fake data to this component, in which case ignore this warning.

16. warning.js:33 Warning: Failed prop type: Invalid prop `children` supplied to `MainContentLayout`, expected a ReactNode.

        in MainContentLayout (created by Connect(MainContentLayout))
        in Connect(MainContentLayout) (created by TeaserListLayout)
        in div (created by TeaserListLayout)
        in TeaserListLayout (created by TeaserListOptimistic)
        in TeaserListOptimistic (created by ContentMapperLayout)
        in ContentMapperLayout (created by UniversalComponent)
        in UniversalComponent (created by Relay(UniversalComponent))
        in Relay(UniversalComponent) (created by Connect(Relay(UniversalComponent)))
        in Connect(Relay(UniversalComponent)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in main (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

17. warning.js:33 Warning: RelayContainer: component `TeaserLayout` was rendered with variables that differ from the variables used to fetch fragment `blogPost`. The fragment was fetched with variables `(not fetched)`, but rendered with variables `{}`. This can indicate one of two possibilities:
    - The parent set the correct variables in the query - `TeaserLayout.getFragment('blogPost', {...})` - but did not pass the same variables when rendering the component. Be sure to tell the component what variables to use by passing them as props: `<TeaserLayout ...  />`.
    - You are intentionally passing fake data to this component, in which case ignore this warning.

18. warning.js:33 Warning: RelayContainer: component `StoryCollectionComponent` was rendered with variables that differ from the variables used to fetch fragment `blog`. The fragment was fetched with variables `(not fetched)`, but rendered with variables `{}`. This can indicate one of two possibilities:
    - The parent set the correct variables in the query - `StoryCollectionComponent.getFragment('blog', {...})` - but did not pass the same variables when rendering the component. Be sure to tell the component what variables to use by passing them as props: `<StoryCollectionComponent ...  />`.
    - You are intentionally passing fake data to this component, in which case ignore this warning.

19. warning.js:33 Warning: validateDOMNesting(...): \<a> cannot appear as a descendant of \<a>.

        in a (created by TeaserLayout)
        in div (created by TeaserLayout)
        in div (created by TeaserLayout)
        in a (created by I13na)
        in I13na (created by Link)
        in Link (created by OptimisticLink)
        in OptimisticLink (created by TeaserLayout)
        in article (created by Teaser)
        in Teaser (created by TeaserLayout)
        in TeaserLayout (created by Relay(TeaserLayout))
        in Relay(TeaserLayout) (created by StoryCollectionComponent)
        in div (created by StoryCollectionComponent)
        in StoryCollectionComponent (created by Relay(StoryCollectionComponent))
        in Relay(StoryCollectionComponent) (created by HomePageLayout)
        in div (created by I13ndiv)
        in I13ndiv (created by HomePageLayout)
        in HomePageLayout (created by UniversalComponent)
        in UniversalComponent (created by Relay(UniversalComponent))
        in Relay(UniversalComponent) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in main (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

20. warning.js:33 Warning: RelayContainer: component `UniversalComponent` was rendered with variables that differ from the variables used to fetch fragment `mapper`. The fragment was fetched with variables `(not fetched)`, but rendered with variables `{"page":0,"collectionID":21708482}`. This can indicate one of two possibilities:
    - The parent set the correct variables in the query - `UniversalComponent.getFragment('mapper', {...})` - but did not pass the same variables when rendering the component. Be sure to tell the component what variables to use by passing them as props: `<UniversalComponent ... page={...} collectionID={...} />`.
    - You are intentionally passing fake data to this component, in which case ignore this warning.

21. warning.js:33 Warning: RelayContainer: component `PrintEditionLayout` was rendered with variables that differ from the variables used to fetch fragment `storyCollection`. The fragment was fetched with variables `(not fetched)`, but rendered with variables `{}`. This can indicate one of two possibilities:
    - The parent set the correct variables in the query - `PrintEditionLayout.getFragment('storyCollection', {...})` - but did not pass the same variables when rendering the component. Be sure to tell the component what variables to use by passing them as props: `<PrintEditionLayout ...  />`.
    - You are intentionally passing fake data to this component, in which case ignore this warning.

22. warning.js:33 Warning: Failed prop type: The prop `pageInformationStore` is marked as required in `PrintEditionLayout`, but its value is `undefined`.

        in PrintEditionLayout (created by PrintEditionOptimistic)
        in PrintEditionOptimistic (created by ContentMapperLayout)
        in ContentMapperLayout (created by UniversalComponent)
        in UniversalComponent (created by Relay(UniversalComponent))
        in Relay(UniversalComponent) (created by Connect(Relay(UniversalComponent)))
        in Connect(Relay(UniversalComponent)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in main (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

23. warning.js:33 Warning: React does not recognize the `buttonRole` prop on a DOM element. If you intentionally want it to appear in the DOM as a custom attribute, spell it as lowercase `buttonrole` instead. If you accidentally passed it from a parent component, remove it from the DOM element.

        in a (created by Link)
        in Link (created by Button)
        in Button (created by NavigationLayout)
        in div (created by NavigationLayout)
        in div (created by NavigationLayout)
        in div (created by NavigationLayout)
        in div (created by NavigationLayout)
        in NavigationLayout (created by Relay(NavigationLayout))
        in Relay(NavigationLayout) (created by Connect(Relay(NavigationLayout)))
        in Connect(Relay(NavigationLayout)) (created by I13nConnect(Relay(NavigationLayout)))
        in I13nConnect(Relay(NavigationLayout)) (created by MainLayout)
        in div (created by StickyScroller)
        in StickyScroller (created by MainLayout)
        in div (created by MainLayout)
        in MainLayout (created by Relay(MainLayout))
        in Relay(MainLayout) (created by Connect(Relay(MainLayout)))
        in Connect(Relay(MainLayout)) (created by RouteContainer)
        in StaticContainer (created by RouteContainer)
        in RouteContainer (created by RouterContext)
        in RouterContext (created by Router)
        in RelayStaticContainer (created by RelayReadyStateRenderer)
        in RelayReadyStateRenderer (created by IsomorphicRenderer)
        in IsomorphicRenderer (created by IsomorphicRelayRouterContext)
        in IsomorphicRelayRouterContext (created by Router)
        in Router (created by Application)
        in Provider (created by Application)
        in Application (created by RootI13nApplication)
        in RootI13nApplication

24. free-email-newsletter-signup?destination=%2Fnews%2Fmiddle-east-and-africa%2F21737335-former-aide-may-spill-beans-prime-minister-pressure-binyamin:1 [DOM] Found 2 elements with non-unique id #user-login: (More info: https://goo.gl/9p2vKq) <form action=​"https:​/​/​stage.economist.com/​user/​login?destination=%2Ffree-email-newsletter-signup" accept-charset=​"UTF-8" method=​"post" id=​"user-login" class=​"user-menu-login-form">​…​</form>​ <form action=​"https:​/​/​stage.economist.com/​user/​login?destination=/​newsletters" accept-charset=​"UTF-8" method=​"post" id=​"user-login" class=​"user-menu-login-form">​…​</form>​
