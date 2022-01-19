- 👋 Hi, I’m @saidul629
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
saidul629/saidul629 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
 header:
  github_docs: GitHub Docs
  contact: Contact
  notices:
    ghae_silent_launch: GitHub AE is currently under limited release. Please <a href="https://enterprise.github.com/contact">contact our Sales Team</a> to find out more.
    release_candidate:
      # The version name is rendered before the below text via includes/header-notification.html
      ' is currently available as a release candidate. For more information, see "<a href="/admin/overview/about-upgrades-to-new-releases">About upgrades to new releases</a>."'
    localization_complete:
      We publish frequent updates to our documentation, and translation of this page may still be in progress.
      For the most current information, please visit the
      <a id="to-english-doc" href="/en">English documentation</a>.
      If there's a problem with translations on this page, please
      <a href="https://github.com/contact?form[subject]=translation%20issue%20on%20docs.github.com&form[comments]=">let us know</a>.
    localization_in_progress:
      Hello, explorer! This page is under active development or
      still in translation. For the most up-to-date and accurate information,
      please visit our
      <a id="to-english-doc" href="/en">English documentation</a>.
    early_access: 📣 Please <b>do not share</b> this URL publicly. This page contains content about an early access feature.
    release_notes_use_latest: Please use the latest release for the latest security, performance, and bug fixes.
    # GHES release notes
    ghes_release_notes_upgrade_patch_only: 📣 This is not the <a href="#{{ latestPatch }}">latest patch release</a> of Enterprise Server.
    ghes_release_notes_upgrade_release_only: 📣 This is not the <a href="/enterprise-server@{{ latestRelease }}/admin/release-notes">latest release</a> of Enterprise Server.
    ghes_release_notes_upgrade_patch_and_release: 📣 This is not the <a href="#{{ latestPatch }}">latest patch release</a> of this release series, and this is not the <a href="/enterprise-server@{{ latestRelease }}/admin/release-notes">latest release</a> of Enterprise Server.
picker:
  toggle_picker_list: Toggle picker list
release_notes:
  banner_text: GitHub began rolling these changes out to enterprises on
search:
  need_help: Need help?
  placeholder: Search topics, products...
  loading: Loading
  no_results: No results found
  search_results_for: Search results for
  no_content: No content
  matches_displayed: Matches displayed
homepage:
  explore_by_product: Explore by product
  version_picker: Version
toc:
  getting_started: Getting started
  popular: Popular
  guides: Guides
  whats_new: What's new
  videos: Videos
pages:
  article_version: 'Article version'
  miniToc: In this article
  contributor_callout: This article is contributed and maintained by
  all_enterprise_releases: All Enterprise releases
errors:
  oops: Ooops!
  something_went_wrong: It looks like something went wrong.
  we_track_errors: We track these errors automatically, but if the problem persists please feel free to contact us.
  page_doesnt_exist: It looks like this page doesn't exist.
support:
  still_need_help: Still need help?
  contact_support: Contact support
  ask_community: Ask the GitHub community
survey:
  able_to_find: Did this doc help you?
  yes: Yes
  no: No
  comment_yes_label: Let us know what we do well
  comment_no_label: Let us know what we can do better
  optional: Optional
  required: Required
  email_placeholder: email@example.com
  email_label: If we can contact you with more questions, please enter your email address
  email_validation: Please enter a valid email address
  send: Send
  feedback: Thank you! We received your feedback.
  not_support: If you need a reply, please contact support instead.
  privacy_policy: Privacy policy
contribution_cta:
  title: Help us make these docs great!
  body: All GitHub docs are open source. See something that's wrong or unclear? Submit a pull request.
  button: Make a contribution
  or: Or,
  to_guidelines: learn how to contribute.
products:
  graphql:
    reference:
      fields: Fields
      arguments: Arguments
      name: Name
      type: Type
      description: Description
      input_fields: Input fields
      return_fields: Return fields
      implemented_by: Implemented by
      values: Values
      possible_types: Possible types
      preview_notice: Preview notice
      deprecation_notice: Deprecation notice
  rest:
    reference:
      parameters: Parameters
      response: Response
      code_sample: Code sample
      code_samples: Code samples
      preview_notice: Preview notice
      preview_notices: Preview notices
      see_preview_notice: See preview notice
      see_preview_notices: See preview notices
      preview_header_is_required: This header is <strong>required</strong>
footer:
  all_rights_reserved: All rights reserved
  terms: Terms
  privacy: Privacy
  security: Security
  product:
    heading: Product
    links:
      features: Features
      security: Security
      enterprise: Enterprise
      case_studies: Case Studies
      pricing: Pricing
      resources: Resources
  platform:
    heading: Platform
    links:
      developer_api: Developer API
      partners: Partners
      atom: Atom
      electron: Electron
      github_desktop: GitHub Desktop
  support:
    heading: Support
    links:
      help: Help
      community_forum: Community Forum
      training: Training
      status: Status
      contact_github: Contact GitHub
  company:
    heading: Company
    links:
      about: About
      blog: Blog
      careers: Careers
      press: Press
      shop: Shop
product_landing:
  quickstart: Quickstart
  reference: Reference
  overview: Overview
  guides: Guides
  code_examples: Code examples
  search_code_examples: Search code examples
  show_more: Show more
  explore_people_and_projects: Explore people and projects
  sorry: Sorry, there is no result for
  no_example: It looks like we don't have an example that fits your filter.
  try_another: Try another filter or add your code example.
  no_result: Sorry, there are no guides that match your filter.
  learn: Learn how to add a code example
  communities_using_discussions: Communities using discussions
  add_your_community: Add your community
  sponsor_community: GitHub Sponsors community
  supported_releases: Supported releases
  release_notes_for: Release notes for
  upgrade_from: Upgrade from
  browse_all_docs: Browse all docs
  explore_release_notes: Explore release notes
product_guides:
  start: Start
  start_path: Start path
  learning_paths: '{{ productMap[currentProduct].name }} learning paths'
  learning_paths_desc: Learning paths are a collection of guides that help you master a particular subject.
  guides: '{{ productMap[currentProduct].name }} guides'
  more_guides: more guides
  load_more: Load more guides
  all_guides: 'All {{ productMap[currentProduct].name }} guides'
  filter_instructions: Filter the guide list using these controls
  filters:
    type: Type
    topic: Topic
    all: All
  guides_found:
    multiple: '{n} guides found'
    one: 1 guide found
    none: No guides found
  guide_types:
    overview: Overview
    quick_start: Quickstart
    tutorial: Tutorial
    how_to: How-to guide
    reference: Reference
learning_track_nav:
  prevGuide: Previous guide
  nextGuide: Next guide
toggle_images:
  off: Images are off, click to show
  on: Images are on, click to hide
  hide_single: Hide image
  show_single: Show image
scroll_button:
  scroll_to_top
