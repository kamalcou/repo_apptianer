# repo_apptianer
apptainer build spack_container.sif spack_container.def 

mkdir my_overlay

apptainer shell --overlay my_overlay/ spack_container.sif
