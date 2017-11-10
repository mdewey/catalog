task :pdf do
  system "asciidoctor-pdf -a pdf-stylesdir=src -a pdf-fontsdir=fonts -a pdf-style=sdg -o output/catalog.pdf src/master.adoc"
end

task :watch do
  system "find src -type f | entr -r rake pdf"
end
