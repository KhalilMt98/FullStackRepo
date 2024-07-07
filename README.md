Steps I followed:

1 Created FullStackRepo, FrontEndRepo, and BackEndRepo.
2 cloned each locally.
2 Created client.py in FrontEndRepo.
3 Created server.py in BackEndRepo.
4 Created config.yaml in FullStackRepo.
5 Added FrontEndRepo and BackEndRepo as submodules to FullStackRepo via git submodules add ... and gave them names "frontend" and "backend", respectively.
6 Modified files in submodules to be able to retrieve from yaml.
( All along: add, commit, push)
7 Using "python client.py" and "python server.py" while in "frontend" and "backend", repectively, one can see the output of the submodules.

What others should do to access submodules from my public FullStackRepo:

1 Write git clone --recurse-submodules ...(url of FullStackRepo)
2 Go to folder
3 Write git submodule update --remote
