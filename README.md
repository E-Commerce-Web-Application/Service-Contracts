## This is the service contracts repository

## CAREFULLY READ FULL GUIDELINES

## Steps to integrate service contracts from the central services repository (This) to your main project.

- run command `git submodule add <service_contracts_repo_url> <local_file_path>`
- local file path you can set as ./app/proto, and make sure not to create proto folder inside the app directory before running this command
- If the submodule is successfully added, then you have to push the latest updates of your project with submodule integrated into the remote repository.

## Other vital things (Must to follow)

- Do not manually edit the proto files inside your main project.
- If you want to make any changes to your service contract, you can clone the service-contracts repository and then make your change/changes and push to the remote repo of service-contracts
- You can follow the same step if you want to create your service proto file.
- Crucial fact that you must do is after making any changes to the service-contracts repo, make sure to update the GitHub submodule inside your main project, so in order to do that, you can run `git submodule update --remote --merge` command.
- And then make sure to push your latest update to your main remote repository.
- By following these practices ensure the consistency of service contracts within this entire Microservices project, so provide your best contribution to maintain this consistency and further project goals.

## Thank you