# repo_apptianer
apptainer build spack_container.sif spack_container.def 

mkdir my_overlay

apptainer shell --overlay my_overlay/ spack_container.sif

spack install openmpi

spack load openmpi
  
. /opt/spack/share/spack/setup-env.sh

spack load openmpi
