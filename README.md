# octopress-twitter-aside
An Octopress 2.0 twitter aside plugin to embed twitter timelines, latest tweets, etc.

## Installation

Get the plugin.

```
> git clone https://github.com/raisedadead/octopress-twitter-aside.git ./source/_includes/custom/asides/ota
```

## Configuration

1. Create a new widget at [this link](https://twitter.com/settings/widgets)
2. Copy the generated HTML code and paste it in a notepad.
3. Search for `data-widget-id`. You should see something like `data-widget-id="xxxxxxxxxxxxxxxxx"`.
4. Copy the `xxxxxxxxxxxxxxxxx` numeric id. This is your `twitter_widget_id`.
5. Edit/Add the below in `_config.yml`

```
# Twitter
twitter_user: username
twitter_widget_id: xxxxxxxxxxxxxxxxx
```
