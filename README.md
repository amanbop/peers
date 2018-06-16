Simple API to parse data from the given two files. Data files should be located in data_dir. For usage see read_data.rb

- PeerData - Loads files as CSV tables
- PeerProcess - Processes the CSV tables and provides output

Install bundler gem

```gem install bundler```

Install rspec and dependcies

```bundle install```

Test run the API

```ruby read_data.rb```

Run rspec tests

```rspec spec/peer_process_spec.rb```

