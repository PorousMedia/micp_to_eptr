# micp_to_eptr

  Estimate the mipv cut-off of MICP data.

  Parameters
  ----------
  micp_data : float, dataframe\
      Columns in the order : Pressure (psia)	Pore Radius (µm)	Incremental Pore Volume (mL/g)	Cumulative Pore Volume (mL/g).\
  threshold : float, Optional\
      Threshold for applying mipv. Default is 0.99.\
  show_data : bolean, Optional\
      An option to show details of mipv cut-off point. Default is True.

  Returns
  -------
   micp_data : float, dataframe\
      micp_data input truncated at the mipv cut-off. Columns in the order : Pressure (psia)	Pore Radius (µm)	Incremental Pore Volume (mL/g)	Cumulative Pore Volume (mL/g). 
