# Datadog IoT Agent + Basicstation on balenaCloud


# Datadog
A sample repo that shows how to use Datadog IoT Agent in combination with another application, for monitoring device metrics.

You do need a Datadog API Key, so, ensure you have signed up for an account with them and grabbed your API Key as outlined in their Docs here:  https://docs.datadoghq.com/getting_started/agent/#configuration

Then in balenaCloud, create an Environment Variable with that information, using the name `DD_API_KEY` and the value of the key.

In the Datadog dashboard, you can then inspect the metrics coming from your devices.


# Basicstation

Repo: https://github.com/xoseperez/basicstation-docker
