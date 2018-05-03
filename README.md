# clang-tooling-sample
This is a simple clang tool for getting started with building source code analysis or source to source transformation 

# Step 1: 
## Modify Makefile
		
		LLVM_SRC_PATH := /home/bernard/Workspace/LLVM/llvm-5.0.0.src
		to 
		LLVM_SRC_PATH := /your/llvm/source/path


		LLVM_BUILD_PATH := /home/bernard/Workspace/LLVM/llvm-5.0.0.src/build
		to 
		LLVM_BUILD_PATH := /your/llvm/source/build/path

# Step 2:
		`make`

# Step 3: 
### Check apps folder where your sample program is placed.
### Modify the compile_commands.json to your directory structure pointing to your sample application

# Step 4:
### ./run.sh 


# Step 5: 
## If it run you are good to go and start looking at src/Sample.cpp for modification. 








