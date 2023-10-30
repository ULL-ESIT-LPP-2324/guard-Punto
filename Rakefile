task :default => :doit

desc "Ejecutar las espectativas de la clase Punto"
task :doit do
  sh "rspec -I. spec/punto_spec.rb"
end

desc "Ejecutar con documentacion"
task :doc do
  sh "rspec -I. spec/punto_spec.rb --format documentation"
end
