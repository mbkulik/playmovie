task :default => [:install]

task :install do
	FileUtils.cp "playmovie", "#{Dir.home}/bin"
end

task :uninstall do
	FileUtils.rm "#{Dir.home}/bin/playmovie"
end
