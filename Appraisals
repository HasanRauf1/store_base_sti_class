RAILS_VERSIONS = %w(
  4.0.0
  4.0.1
  4.0.2
  4.0.3
  4.0.4
  4.0.5
  4.0.6
  4.0.7
  4.0.8
  4.0.9
  4.0.10
  4.0.11
  4.0.11.1
  4.0.12
  4.0.13
  4.1.0
  4.1.1
  4.1.2
  4.1.3
  4.1.4
  4.1.5
  4.1.6
  4.1.7
  4.1.7.1
  4.1.8
  4.1.9
  4.1.10
  4.1.11
  4.1.12
  4.1.13
  4.1.14
  4.1.14.1
  4.1.14.2
  4.1.15
  4.2.0
  4.2.1
  4.2.2
  4.2.3
  4.2.4
  4.2.5
  4.2.5.1
  4.2.5.2
  4.2.6
  4.2.7
  4.2.7.1
  4.2.8
  4.2.9
  4.2.10
  5.0.0
  5.0.0.1
  5.0.1
  5.0.2
  5.0.3
  5.0.4
  5.0.5
  5.0.6
  5.1.0
  5.1.1
  5.1.2
  5.1.3
  5.1.4
  5.2.0.beta2
)

RAILS_VERSIONS.each do |version|
  appraise "rails_#{version}" do
    gem 'activerecord', version
  end
end
