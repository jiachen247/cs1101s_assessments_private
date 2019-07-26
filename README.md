# css1101s_assessments_private

## To add submodule

`[jiachen@jiachen cs1101s_assessments]$ GIT_SSH_COMMAND="ssh -i ~/.ssh/cs1101s" git submodule add git@github.com:jiachen247/cs1101s_assessments_private.git practicals`

## If submodule added after cloning
`GIT_SSH_COMMAND="ssh -i ~/.ssh/cs1101s" git submodule --update --init`

## To Clone 
`GIT_SSH_COMMAND="ssh -i ~/.ssh/cs1101s" git clone --recursive git@github.com:jiachen247/cs1101s_assessments.git cs1101s`

## To update 

`GIT_SSH_COMMAND="ssh -i ~/.ssh/cs1101s" git pull --recurse-submodules`
`GIT_SSH_COMMAND="ssh -i ~/.ssh/cs1101s" git submodule update --remote --recursive`
