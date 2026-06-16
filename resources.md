Please see attached for some 'Idiot's guides to…", all about running HadGEM3-GC31-LL on ARCHER2.  In particular...

Part 1: This gives basic setup instructions (i.e. to connect to everything e.g. PUMA2 from ARCHER2 and vice versa), and then explains how to get a standard CMIP6 preindustrial suite working - a good place to start with the rest.

[Idiot's Guide, Part 1 - Setting up and running PI.pdf](https://github.com/user-attachments/files/29003227/Idiot.s.Guide.Part.1.-.Setting.up.and.running.PI.pdf)

Part 2: This gives detailed instructions on creating a new LSM, including: creating a new bathymetry, using this to create the mesh mask files, rebuilding them into one, using this to create the coupling weights and finally using these to create new ancillaries.  This is an alternative method, which I am perhaps pompously calling the Williams Process, to the official Met office method of generating coupling weights - but we (especially Zikun, many thanks to you) have fairly robustly tested them and are fairly confident that they are unacceptable level of "right".

[Idiot's Guide, Part 2 - Setting up new LSM.pdf](https://github.com/user-attachments/files/29003237/Idiot.s.Guide.Part.2.-.Setting.up.new.LSM.pdf)

Part 3: This gives detailed instructions on how to modify the resulting ancillaries, in order to fill them with data appropriate for a given time period, using the mid-Pliocene as an example.

[Idiot's Guide, Part 3 - Changing ancillaries and other science modifications.pdf](https://github.com/user-attachments/files/29003243/Idiot.s.Guide.Part.3.-.Changing.ancillaries.and.other.science.modifications.pdf)

Part 4: This gives instructions on how to actually run the suite when everything is ready, monitor it, check output, and fix potential problems.

[Idiot's Guide, Part 4 - Running, monitoring and fixing problems.pdf](https://github.com/user-attachments/files/29003262/Idiot.s.Guide.Part.4.-.Running.monitoring.and.fixing.problems.pdf)

---

There are also some existing resources:

* Dan has written some [documentation about running HadCM3](https://github.com/danlunt1976/UM_Bristol/blob/main/HadCM3_user_notes.md)
* Seb documented the [Bristol HadGEM3 simulations](https://github.com/sebsteinig/hadgem3-eocene)
* This community's resources can be found on [our GitHub](https://github.com/orgs/PalaeoClimateModellingUK/repositories)
