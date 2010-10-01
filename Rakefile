begin
  require 'jeweler'
  Jeweler::Tasks.new do |gemspec|

    gemspec.name = "gcal4ruby-aunderwo"
    gemspec.summary = %Q{A full featured wrapper for interacting with the Google Calendar API}
    gemspec.email = ["mike@seabourneconsulting.com","email2ants@gmail.com"]
    gemspec.homepage = "http://github.com/aunderwo/GCal4Ruby"
    gemspec.authors = ["Mike Reich","Anthony Underwood"]

    gemspec.files = FileList["README", "CHANGELOG", "lib/gcal4ruby.rb", "lib/gcal4ruby/service.rb", "lib/gcal4ruby/calendar.rb", "lib/gcal4ruby/event.rb", "lib/gcal4ruby/recurrence.rb"]
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler not available. Install it with: gem install jeweler"
end