This repository does not seek to claim ownership of any content it hosts.

Documents hosted on this page are used solely for the training of AI software. These documents are used to aid in the randomness and/or decision making of the aforementioned software. Examples of software that utilize these documents include (at the time of writing): `Project Savant` and its' respective `Rewrite`

All rights belong to each documents respective copyright owners (see below).


# Included Documentation

Harry Potter Books 1-7: Authored By: **J.K. Rowling**

# Licensing

Notwithstanding the provisions of sections 106 and 106A, the fair use of a copyrighted work, including such use by reproduction in copies or phonorecords or by any other means specified by that section, for purposes such as criticism, comment, news reporting, teaching (including multiple copies for classroom use), scholarship, or **research**, __is not an infringement of copyright.__ In determining whether the use made of a work in any particular case is a fair use the factors to be considered shall include—

- (1) the purpose and character of the use, including whether such use is of a commercial nature or is for nonprofit educational purposes; 
- (2) the nature of the copyrighted work;
- (3) the amount and substantiality of the portion used in relation to the copyrighted work as a whole; and
- (4) the effect of the use upon the potential market for or value of the copyrighted work.

The fact that a work is unpublished shall not itself bar a finding of fair use if such finding is made upon consideration of all the above factors.

*(Pub. L. 94–553, title I, § 101, Oct. 19, 1976, 90 Stat. 2546; Pub. L. 101–650, title VI, § 607, Dec. 1, 1990, 104 Stat. 5132; Pub. L. 102–492, Oct. 24, 1992, 106 Stat. 3145.)*

## Declaration of Intent

The content contained in this repository is intended for the following use cases:

- Sample Text Generation for the Message Evaluation API contained within `Project Savant`

This API recieves a payload containing a message sent by a user. It uses the content contained within this repository to generate no more than 16 substrings of length *n* (where *n* is equal to length of the original payload). These substrings are then ran through a series of tests, which quantify properties such as: 

- Usage and Diversity in Whitespace characters
- Usage of Capitalization
- Diversity of Included Characters
- Usage and Diversity of Words
- Frequency and Diversity of all lowercase ASCII Characters

The results of these tests against each of the 8 to 16 sample texts generated earlier are then averaged. The average result of each test is then compared to the results of the original payload to determine the likelihood of the payload message being a valid string.

# Questions or Concerns

If you have any questions about the usage of any content contained within this repository, please reach out to @Savant-Dev
