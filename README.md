# QIA-Hackathon2023

Qualcomm-KAIST Innovation Award 2023

## Description

This repository consists of Phase1 and Phase2.

## Getting Started

### Dependencies

* Describe any prerequisites, libraries, OS version, etc., needed before installing program.
* ex. Windows 10

### Installing

* How/where to download your program
* Any modifications needed to be made to files/folders
1. convert all the data files including question file to csv format.
2. Specifically, name the question csv file as question.csv.

### Executing program

* How to run the program
* Phase1
1. Run all cells in Phase1.ipynb
2. basemodel_result.csv will be made to /content/drive/MyDrive/qia-hackathon2023/data/{now}/basemodel_result.csv, where {now} is strftime("%m_%d_%H")
for example, if time is 18:00 May 24 6 PM now in Korea time, now = 05_24_18

* Phase2
1. download the jupyter notebook file to google drive 
2. download the question.csv file, train_data.csv file and test_data.csv file to /content/drive/MyDrive/kaggle/QIA2023/data directory of google drive.
3. Run all cells in Phase2 folder in order of embed_0.55.ipynb, train_0.55.ipynb, test_naive_0.55.ipynb.

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Contributors names and contact info

Wonjun Chang KAIST wj0559@kaist.ac.kr
Seungwoo Han KAIST preston119@kaist.ac.kr

## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]()
* 0.1
    * Initial Release

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* [dbader](https://github.com/dbader/readme-template)
* [zenorocha](https://gist.github.com/zenorocha/4526327)
* [fvcproductions](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46)
