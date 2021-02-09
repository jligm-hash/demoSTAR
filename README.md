# STAR demo for beginners

This is the demo STAR for beginners to make it easy for beginners to use STAR.

## How to download and run demo STAR? (For Linux/Mac user)

**Step 0**, before you run this demo, you are supposed to have `git` to download the source code. 

- Please type `git` and run in the terminal to check whether you have installed the `git`. If not, the terminal will show you the one-line code to install `git`.

- You can also use other command to download the source code in this page. However, you may meet with the permission and software safety problems when using other methods to download the source code. If you come up with such problems in Mac, you should go to `system perferences/Security & Privacy` option to allow the software.

**Step 1**, clone this demo respository, run

```git clone https://github.com/jligm-hash/demoSTAR```

- After this step, you will see `demo` folder is inside the `demoSTAR` folder. Inside `demo` folder, there are `data` folder, `result` folder, `linuxOS` folder, `macOS` folder, `starLinux.sh`, `starMac.sh`.

**Step 2**, download the [genome folder](https://drive.google.com/drive/folders/1E_RJofRoUjM8AZc5CKcFLID7qXqLzozH?usp=sharing) we prepared for you and copy the `genome` folder (including the files in it) into the `data` folder.

- After this step (downloading the files in genome folder), there should be `genome` folder, `RNAseq` folder and `result` folder inside the `data` folder. 
The important files for your running should inside `genome` folder and they are `Genome`, `chrLength.txt`, `geneInfo.tab`, `chrName.txt`, `genomeParameters.txt`, `SA`, `chrNameLength.txt`, `sjdbInfo.txt`, `SAindex`, `chrStart.txt`, `sjdbList.fromGTF.out.tab`, `chr21.hg37.fa`, `exonGeTrInfo.tab`, `sjdbList.out.tab`, `chr21.hg37.gtf`, `exonInfo.tab`, `transcriptInfo.tab`.

- Pay attention to the name of `genome` folder. If its name is not `genome`, you may get the error and need to reverse the genome folder name in `starLinux.sh` or `starMac.sh`.

- As an alternative, you can generate the `genome` folder instead of downloading and setting the directory of them. Just try to run the script `genomeLinux.sh` or `genomeMac.sh` in the command (in the working directory of `./demo`). Once you have run it successfully for one time, you don't have to run it every time.

**Step 3**, make sure you change the working directory to `./demo`, for example, you may run

```cd ./demoSTAR/demo```

**Step 4**, start running demo STAR

For linux user, run `bash starLinux.sh` or `./starLinux.sh`

For Mac user, run `bash starMac.sh` or `./starMac.sh`

**Step 5**, check your results in `result` folder.

## Notes

- For the demo STAR running, the memory (or RAM) more than 6GB is recommended.

- For original released information on STAR, please turn to [STAR](https://github.com/alexdobin/STAR).
