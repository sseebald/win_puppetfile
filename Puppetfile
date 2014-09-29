# This is a Puppetfile, which describes a collection of Puppet modules. For
# format and syntax examples, see one of the following resources:
#
# https://github.com/rodjek/librarian-puppet/blob/master/README.md
# https://github.com/adrienthebo/r10k/blob/master/README.markdown
#
# Brief example:
#
#   mod 'puppetlabs/stdlib', '4.1.0'
#
# The default production environment for the SE Team is just going to pull in
# the current version of our "profile" module from the Forge and whatever
# dependencies it has.

forge "https://forge.puppetlabs.com"

# PL Modules
mod 'puppetlabs/git', '0.0.3'
mod 'puppetlabs/dism', '1.0.0'
mod 'puppetlabs/reboot', '0.1.8'
mod 'puppetlabs/registry', '1.0.3'
mod 'puppetlabs/acl', '1.0.3'
mod 'puppetlabs/pe_gem', '0.0.1'
mod 'puppetlabs/vcsrepo', '1.1.0'
mod 'puppetlabs/powershell', '1.0.3'
mod 'opentable/windowsfeature', '0.2.0'
mod 'stdlib',
  :git => 'git://github.com/puppetlabs/puppetlabs-stdlib.git',
  :ref => '4.1.0'
# Community Modules

mod 'opentable/iis', '1.2.0'

# TSE modules - either maintained under seteam
# or by individual SE's
# mod 'seteam/profile', '0.2.4'
mod 'dotnet',
  :git => 'https://github.com/sseebald/dotnet.git',
  :ref => '891996e5c80dc06ed90019b8d45e3ba013d0377c'
mod 'chocolatey',
  :git => 'https://github.com/sseebald/chocolatey.git',
  :ref => '4d81e1c75b12d4f42bda5fb74f4bf9abccfc4a0b'
mod 'cmsapp',
  :git => 'https://github.com/sseebald/cmsapp.git',
  :ref => '0bfd34ffd1720baaf6e04b3cac1e4943dc394ee4'
mod 'pe_windows_shortcuts',
  :git => 'https://github.com/sseebald/pe_windows_shortcuts.git',
  :ref => '9c3350b6b7900a7be30221c4c75832eb730742f7'
mod 'staging',
  :git => 'https://github.com/reidmv/puppet-module-staging.git',
  :ref => 'seteam_puppet_environments'
mod 'role',
  :git => 'https://github.com/sseebald/win_role.git',
  :ref => '01d46482ac81c3fb56c00ac20021f2846915287a'
mod 'profile',
  :git => 'https://github.com/sseebald/win_profile.git',
  :ref => '2021719fe0afc909c493d3d32322845755c60ec3'
