### Warning
This is a patched version that drops `pwd` logic from `load_raw_data_with_mhd` and assumes that
`meta_dict['ElementDataFile']` always contains an absolute filepath. For details see
https://github.com/yanlend/mhd_utils/issues/6.

# mhd_utils
Reading and writing .mhd files in python, extension from https://sites.google.com/site/pjmedphys/

Extended functionality:
- more datatypes supported
- handles 'ElementNumberOfChannels'
- allows to write meta-information
