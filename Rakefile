task :pdf do
  system "asciidoctor-pdf -o output/catalog.pdf src/master.adoc"
end

task :watch do
  system "find src -type f | entr -r rake pdf"
end
