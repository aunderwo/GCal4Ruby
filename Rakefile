begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "gcal4ruby-aunderwo"
    gem.summary = %Q{A full featured wrapper for interacting with the Google Calendar API}
    gem.email = ["mike@seabourneconsulting.com","email2ants@gmail.com"]
    gem.homepage = "http://github.com/aunderwo/GCal4Ruby"
    gem.authors = ["Mike Reich","Anthony Underwood"]

    gem.files = FileList["README", "CHANGELOG", "lib/gcal4ruby.rb", "lib/gcal4ruby/service.rb", "lib/gcal4ruby/calendar.rb", "lib/gcal4ruby/event.rb", "lib/gcal4ruby/recurrence.rb"]

    # gem is a Gem::Specification... see http://www.rubygems.org/read/chapter/20 for additional settings
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler not available. Install it with: sudo gem install technicalpickles-jeweler -s http://gems.github.com"
end