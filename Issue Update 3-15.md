# POST Issue Update for Week of 4/15

#### 1.[Issue #7, 4/8] Help Chelsea with table component
    a.4/19 - EXTENDED
    b.gap75
      i.[gap75, 4/16] - Tried to use the same Plotly request for data as in the Graph Component, but ran into dependency issues. Worked on getting them resolved.
      ii.[gap75, 4/17] - Dependency issues resolved, but ran into new bug. The current issue is that the HTML is designed to grab data from the TS file stored as an array in a field of the TableComponent class. Unfortunately, since the JSON data from the Plotly request is operated on within an asynchronous function, I cannot access the data field for the class.
      iii.[gap, 4/18] - Still debugging previous issue. Will probably try to make a more generic GET request for data instead of using the Plotly function.

#### 2. [Issue #6, 3/16] Implement table component using angular
    a.4/15-EXTENDED
    b.yw299
      i. [yw299, 4/16]Start to code the .ts for table component based on the existing code of graph
      ii.[yw299, 4/18]Asked for Giancarlo’s help on coding .ts for table component

#### 3. [Issue #4 , 3/4] Research on iOS alternatives to ODK
    a.4/15- Continued
    b.Rjt95
      i.[rjt95, 4/17] Downloaded and exploring enketo data options
          Installed and played with:
          MapYourWorld
          KoboToolbox
          OpenClinica

####4. [Issue #8 , 3/15] Research on deep learning methods using Python Tensorflow
    a.4/15- Continued
    b.rt457
      i.[rt457,  4/16] - Read through documentations and API
      ii.[rt457,  4/17] - Completed some tutorials and researched ways POST data can be analyzed to help operations
      iii.[rt457,  4/18] - Continued working on tutorials 

#### 5. [Issue #4, 4/15]  Working on new things to add to email service 
    a.4/15- continued
    b.Nb378
      i. [nb378, 4/16,4/17,4/18] continued looking at how differences in weather affects turbidity and the effects it has on turbidity in order to see how to inform plant operators on upcoming week.  

#### 6. [Issue #9, 4/15] moving auto email server to an AguaClara POST aws
    a.4/15 OPENED
    b.rrr225
      i.[rrr225,4/16,4/17,4/18] making new aws server, redoing the installs needed and fixing bugs and schedulimg for the auto email script
