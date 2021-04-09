- The dataset contains the United Nations General Debate Corpus (UNGDC) covering the period 1970-2018. 

- There are 8,093 speeches in plain text format (UTF8). Speeches are structured by Year (Session). Each speech is named using the following convention: ISO 3166-1 alpha-3 country code, followed by the UN Session number, followed by year. E.g. USA_73_2018.txt.

- An example of using the corpus is presented in RAP.nb.html. This is R Notebook replication file for the data release paper. Full replication set is available from the Harvard Dataverse (http://dx.doi.org/10.7910/DVN/AER5QJ).

- Additional examples are available on GitHub repo for the project here: https://github.com/sjankin/UnitedNations

- The collection also contains a file (Speakers_by_session.csv) recording names and posts of speakers in UN General Debates. Note: before 1994 UN records do not identify the posts of all speakers.

- Original source files contain verbatim daily transcripts of UN General Debate (and any other business on the UN agenda on the same day). Transcripts (in PDF format) were made available by the UN Library and processed to produce the UNGD Corpus as described in the paper. The original source files (PDFs) are in several tarballs: 
	“Raw PDFs 1970-1980.tar.gz”; 
	“Raw PDFs 1981-1990.tar.gz”; 
	“Raw PDFs 1991-2017.tar.gz”;
	"Raw PDFs 2018.tar.gz".    

- When using the UNGDC data, please cite: Alexander Baturo, Niheer Dasandi, and Slava Mikhaylov, "Understanding State Preferences With Text As Data: Introducing the UN General Debate Corpus" Research & Politics, 2017.