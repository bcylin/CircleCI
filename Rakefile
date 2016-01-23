require "json"

task default: "update"

desc "Update json for Ground Control"
task :update do
  settings = {
    version: 1047
  }
  File.write("./ground-control.json", "#{settings.to_json}\n")
end
