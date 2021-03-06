# Xamarin Studio Add-Ins

This is a collection of Xamarin Studio add-ins we've developed at [Olo](http://olo.com) to help us out. (Ok, so it's currently a collection of one, but we promise to add more as we create them!)

## Olo.BuildTools

### System Information

This is an extension to Xamarin Studio's `mdtool` command that allows you to capture information on all the tooling versions currently set up in Xamarin Studio. Essentially, this is the same as what is provided in Xamarin Studio's About dialog. We use this as part of our build processes in order to capture the exact versions used on our build servers when packaging an app.

You can display this output in the console by running:

`mdtool systeminfo -c`

You can also pipe the output to a file by running:

`mdtool systeminfo -f:toolversions.txt`