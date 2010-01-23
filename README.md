# Shoulda TextMate bundle

The Shoulda[http://github.com/thoughtbot/shoulda] gem makes it easy to write elegant, understandable, and maintainable Ruby tests.

To install with Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git@github.com:shaliko/shoulda-tmbundle.git "Shoulda.tmbundle"

To install without Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    wget http://github.com/shaliko/shoulda-tmbundle/tarball/master
    tar zxf shaliko-shoulda-tmbundle*.tar.gz
    rm shaliko-shoulda-tmbundle*.tar.gz
    mv shaliko-shoulda-tmbundle* "Shoulda.tmbundle"

# Snippets

* Shoulda::ActionController::Macros
  * should_assign_to (sat)
  * should_filter_params (sfp)
  * should_not_assign_to (snat)
  * should_not_set_the_flash (snsft)
  * should_redirect_to (srt)
  * should_render_template (srt)
  * should_render_with_layout (srwl)
  * should_render_without_layout (srwl)
  * should_respond_with (srw)
  * should_respond_with_content_type (srwct)
  * should_route (sr)
  * should_set_session (sss)
  * should_set_the_flash_to (sstft)
* Shoulda::ActiveRecord::Macros
  * should_have_db_columns (shdcs)
  * should_ensure_value_in_range (sevir)
  * should_have_class_methods (shcm)
  * should_ensure_length_is (seli)
  * should_ensure_length_in_range (selir)
  * should_ensure_length_at_least (selat)
  * should_allow_values_for (savf)
  * should_not_allow_mass_assignment_of (snama)
  * should_have_db_column (shdc)
  * should_have_db_indeces (shdis)
  * should_have_db_index (shdi)
  * should_have_one (sho)
  * should_have_many (shm)
  * should_have_many :through => :refference (shmt)
  * should_have_many :dependent => :destroy (shmd)
  * should_have_and_belong_to_many (shabtm)
  * should_have_instance_methods (shim)
  * should_not_allow_values_for (snavf)
  * should_have_readonly_attributes (shra)
  * should_validate_presence_of (svpo)
  * should_validate_uniqueness_of (svuo)
  * should_validate_acceptance_of (svao)
  * should_validate_numericality_of (svno)
* Shoulda::Macros
  * should_change (sch)
  * should_create (scr)
  * should_destroy (sd)
  * should_not_change (snch)

# Credits

Shoulda.tmbundle is maintained by {Shalva Usubov}[mailto:shaliko@ezid.ru], and is funded by Hashtrain[http://hashtrain.com], LLC.

# License

Shoulda.tmbundle is Copyright © 2010 Shalva Usubov, Hashtrain. It is free software, and may be redistributed under the terms specified in the MIT-LICENSE file.