begin
  require 'jeweler'
  Jeweler::Tasks.new do |gemspec|
    gemspec.name = "gcal4ruby"
    gemspec.summary = %Q{A full featured wrapper for interacting with the Google Calendar API}
    gemspec.email = ["daniel@sykewarrior.com"]
    gemspec.homepage = "https://github.com/buffpojken/GData4Ruby"
    gemspec.authors = ["Buffpojken"]
    gemspec.add_dependency 'buffpojken-gdata4ruby','>= 0.2.1'
    gemspec.files = FileList["README", "CHANGELOG", "lib/gcal4ruby.rb", "lib/gcal4ruby/service.rb", "lib/gcal4ruby/calendar.rb", "lib/gcal4ruby/event.rb", "lib/gcal4ruby/recurrence.rb"]
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler not available. Install it with: gem install jeweler"
end