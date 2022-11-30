v1.9.51
added filter mepr-admin-members-custom-cols
mepr-admin-members-custom-cols
It allows you to add a custom rows to MemberPress → Members page.

example
function mepr_admin_members_cols($tableResults) {
// Do what you need
return $tableResults;
}
add_filter('mepr-admin-members-custom-cols', 'mepr_admin_members_custom_cols');
