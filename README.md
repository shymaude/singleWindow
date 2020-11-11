This repository contains SHYMaude specifications of three single window document circulation systems and QuaTEx specifications of four metrics designed to analyze the systems.

SHYMaude specifications:

1. singleWindow.shymaude contains a SHYMaude specification of a single window document circulation system consisting of one client and N officers processing document packages.
2. singleWindowManaged.shymaude contains a SHYMaude specification of a managed version of the system. A manager has been added to control the number of officers.
3. singleWindowManagedAdjusted.shymaude contains a SHYMaude specification of an adjusted managed version of the system. Manager's algorithm has been fixed.

One can use the translated Maude specification to use it within Maude based systems.
The translated specifications of three systems are contained in corresponding files with the "maude" extension.

The folder "inc" contains dependencies needed for the translated specifications.

QuaTEx specifications in folder "quatex":

1. maxQueueLength.quatex contains a QuaTEx specification of the maximum queue application length seen on the interval [0, 40].
2. maxQueueLengthTime.quatex contains a QuaTEx specification of the time when the maximum queue application length stops to grow on [0, 40].
3. docProcessingTime.quatex contains a QuaTEx specification of the average application processing time on [0, 40].
4. officerBusyTime.quatex contains a QuaTEx specification of the period of time during which an officer is being busy processing applicaitons on [0, 40].