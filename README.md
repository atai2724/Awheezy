# Awheezy
for stepping stone 21
fileConn <- file("README.md")
writeLines(c(
  "# Plant Growth Data ",
  "",
  "## Description",
  "This dataset contains observational data on plant growth under various conditions.",
  "",
  "### Variables:",
  "- **Soil Type:** Type of soil (sandy, loamy, clay).",
  "- **Sunlight Hours:** Daily sunlight in hours.",
  "- **Water Frequency:** How often the plants are watered.",
  "- **Fertilizer Type:** Type of fertilizer used.",
  "- **Temperature:** Environmental temperature (°C).",
  "- **Humidity:** Moisture level (%).",
  "",
  "## License",
  "Please specify the license for using this dataset."(,fileConn)
close(fileConn)

