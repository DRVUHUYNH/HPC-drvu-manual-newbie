# IN HPC WE MUST USE ENVIRONMENT TO INSTALL TOOLS
# INSTALL ENV
## MICROMAMBA
### Check if there is micromamba
```bash 
which micromamba

/usr/local/bin/micromamba
```

### create env
```bash
micromamba create -n <env_name>
```
```bash
warning  libmamba 'root_prefix' set with default value: /home/<username>/micromamba
```
### activate env

```bash
micromamba activate /home/<username>>/micromamba/envs/<env_name>
eval "$(micromamba shell hook --shell bash)"
micromamba activate /home/<username>>/micromamba/envs/<env_name>
```
### Install tools in envs
#### check tools you wnat to install at anaconda.org, replace conda to micromamba