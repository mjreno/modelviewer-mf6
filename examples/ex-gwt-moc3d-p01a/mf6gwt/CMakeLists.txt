install(
  FILES 
    mfsim.lst
    mfsim.nam
    trans.adv
    trans.cbc
    trans.dis
    trans.dsp
    trans.fmi
    trans.ic
    trans.ims
    trans.lst
    trans.mst
    trans.nam
    trans.obs
    trans.obs.csv
    trans.oc
    trans.ssm
    trans.tdis
    trans.ucn
  DESTINATION 
    $<$<PLATFORM_ID:Linux>:${CMAKE_INSTALL_DOCDIR}/>examples/ex-gwt-moc3d-p01a/mf6gwt
)
