# MuleSoft training: DevFundamentals w/Mule-4

The contents in these folders contain solution files for walkthroughs covered each day.

What do these file types mean?

- .jar: most probably a MuleSoft app bundled as a .jar file

- .zip: most probably a RAML specification along with other associated RAML fragments

- .json or .xml: files used as sample data to build input/output schemas for DataWeave


<BR>

## How to import **Mule Application** solution into Studio?


### Step 1:

- Download my **AmericanFlights API Connector** represented as ----> 20e21506-b21d-48ed-811e-431d9b450530.zip (see above in the file list to find it)

- Copy above zip file to your **M2_REPO** directory (M2_REPO is at C:\Users\your_userid\\.m2\repository\ on **Windows** and .m2/repository/ on **Mac**)

- Extract that zip file within the same M2_REPO directory

### Step 2:


- Download the solution .jar file from appropriate day's folder

- Start **Anypoint Studio**

- **Note**: If the Studio's worspace already contains a project with the same name that you plan to import, right-click on the prject and _delete_ it first (don't forget to select the _checkmark_ to delete it from the filesystem as well)

- Within **Package Explorer** section (top-left), right-click anywhere in white space, select **Import** to open the wizard

- Within **Import** wizard, exapand **Anypoint Studio > Packaged Mule application (jar)** and click **Next**

- Browse and select the .jar file that you downloaded, and click **Finish**

- Wait till all necessary dependencies are downloaded (progress is indicated at the bottom-right corner of Studio)

- That's it.  Now, you are ready to either add more content or run and test the mule app


<BR>

## How to import the RAML solution into Anypoint Design Center?

- Download the zip file that represents the RAML specification (no need to unzip it)

- Log into **Anypoit Platform**: https://anypoint.mulesoft.com

- Access **Design Center**.  Click **Create > Specification**

- Provide the name: **American Flights API** (note: if you aready have one by this name, remove/rename the first)

- Once the **API Designer** opens, click on **three-dots** at the top-left and select **Import**

- Click on **Choose File** and point to the zip file you downloaded

- Click **Import**, and select **Yes** if prompted to overwrite the existing .raml file

- Turn on **Mocking Service** (slider on top-right corner)

- Test your API.  When complete, turn off **Mocking Service**

- Publish your API to **Exchange** (there's a button for that too :)  Look at the top-right corner)

<BR>
