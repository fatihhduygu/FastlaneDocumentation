# FastlaneDocumentation

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

## Choose your installation method:

<table width="100%" >
<tr>
<th width="33%"><a href="http://brew.sh">Homebrew</a></td>
<th width="33%">Installer Script</td>
<th width="33%">Rubygems</td>
</tr>
<tr>
<td width="33%" align="center">macOS</td>
<td width="33%" align="center">macOS</td>
<td width="33%" align="center">macOS or Linux with Ruby 2.0.0 or above</td>
</tr>
<tr>
<td width="33%"><code>brew cask install fastlane</code></td>
<td width="33%"><a href="https://download.fastlane.tools">Download the zip file</a>. Then double click on the <code>install</code> script (or run it in a terminal window).</td>
<td width="33%"><code>sudo gem install fastlane -NV</code></td>
</tr>
</table>

# Setting up fastlane
Navigate your terminal to your project's directory and run

```
fastlane init
```

# Set up environment variables

fastlane requires some environment variables set up to run correctly. In particular, having your locale not set to a UTF-8 locale will cause issues with building and uploading your build. In your shell profile add the following lines:

```
export LC_ALL=en_US.UTF-8
export LANG=en_US.UTF-8
```

You can find your shell profile at ~/.bashrc, ~/.bash_profile, ~/.profile or ~/.zshrc depending on your system.

# Fastlane Commands

<table width="100%" >
<tr>
<td width="30%">fastlane actions</td>
<td width="70%">List all available fastlane actions</td>
</tr>
<tr>
<td width="30%">fastlane action[action_name]</td>
<td width="70%">Shows a more detailed description of an action</td>
</tr>
<tr>
<td width="30%">fastlane lanes</td>
<td width="70%">List all available lanes with description</td>
</tr>
<tr>
<td width="30%">fastlane list</td>
<td width="70%">List all available lanes without description</td>
</tr>
<tr>
<td width="30%">fastlane new_action</td>
<td width="70%">Create a new action for fastlane</td>
</tr>
<tr>
<td width="30%">bundle exec fastlane test</td>
<td width="70%">Run it test lane </td>
</tr>
</table>

----
# Fastlane tools

<table width="100%" >
<tr>
<td width="30%">deliver</td>
<td width="70%">Upload screenshots, metadata, and your app to the <b>App Store</b></td>
</tr>
<tr>
<td width="30%">supply</td>
<td width="70%">Upload your <b>Android</b> app and its meta-data to <b>Google Play</b>.</td>
</tr>
<tr>
<td width="30%">snapshot</td>
<td width="70%">Automate taking localized screenshots of your <b>iOS and tvOS apps</b> on every device</td>
</tr>
<tr>
<td width="30%">screengrab</td>
<td width="70%">Automate taking localized screenshots of your <b>Android app</b> on every device.</td>
</tr>
<tr>
<td width="30%">frameit</td>
<td width="70%">Quickly put your screenshots into the right device frames</td>
</tr>
<tr>
<td width="30%">pem</td>
<td width="70%">Automatically generate and renew your push notification profiles</td>
</tr>
<tr>
<td width="30%">sight</td>
<td width="70%">Because you would rather spend your time building stuff than fighting provisioning</td>
</tr>
<tr>
<td width="30%">produce</td>
<td width="70%">Create new iOS apps on iTunes Connect and Dev Portal using the command line</td>
</tr>
<tr>
<td width="30%">cert</td>
<td width="70%">Automatically create and maintain iOS code signing certificates</td>
</tr>
<tr>
<td width="30%">spaceship</td>
<td width="70%">Ruby library to access the Apple Dev Center and iTunes Connect</td>
</tr>
<tr>
<td width="30%">pilot</td>
<td width="70%">The best way to manage your TestFlight testers and builds from your terminal</td>
</tr>
<tr>
<td width="30%">boarding</td>
<td width="70%">The easiest way to invite your TestFlight beta testers</td>
</tr>
<tr>
<td width="30%">gym</td>
<td width="70%">Building your iOS apps has never been easier</td>
</tr>
<tr>
<td width="30%">match</td>
<td width="70%">Easily sync your certificates and profiles across your team using Git</td>
</tr>
<tr>
<td width="30%">scan</td>
<td width="70%">The easiest way to run tests for your iOS and Mac apps</td>
</tr>
</table>


----
This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).Setting up fastlane
