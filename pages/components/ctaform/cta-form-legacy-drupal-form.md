<div class="region region-content pf-content">
    <div data-drupal-messages-fallback="" class="hidden"></div>
    <div class="openid-connect-login-form block block-openid-connect block-openid-connect-login"
        data-drupal-selector="openid-connect-login-form" id="block-openidconnectlogin"
        data-block-plugin-id="openid_connect_login">
        <p>Content editors should now log in using their Red Hat account.</p>
        <p>Please ensure that your Red Hat account has the same email address as used by your account in Drupal. For
            assistance, please contact the RHDP Engineering team or use the 'report a website issue' link in the footer
            below.</p>
        <form action="/user/login" method="post" id="openid-connect-login-form" accept-charset="UTF-8">
            <div><input data-drupal-selector="edit-openid-connect-client-keycloak-login" type="submit"
                    id="edit-openid-connect-client-keycloak-login" name="keycloak"
                    value="Log in with your Red Hat Account" class="button js-form-submit form-submit">
            </div><input autocomplete="off" data-drupal-selector="form-asyxt2zmvxywbbpb5kmu8lrtacvmuu-f0x3-5gg9zs"
                type="hidden" name="form_build_id" value="form-_AsyXT2ZMVXYwbBpB5kmU8lrTacVmUu_f0X3_5Gg9zs">
            <input data-drupal-selector="edit-openid-connect-login-form" type="hidden" name="form_id"
                value="openid_connect_login_form">
        </form>
        <button id="drupalUserLoginToggleVisibility">Legacy login</button>
    </div>
    <div id="block-rhdp-content" data-block-plugin-id="system_main_block"
        class="block block-system block-system-main-block">
        <form class="user-login-form" data-drupal-selector="user-login-form" action="/user/login" method="post"
            id="user-login-form" accept-charset="UTF-8" style="display: block;">
            <div
                class="js-form-item form-item js-form-type-textfield form-type-textfield js-form-item-name form-item-name">
                <label for="edit-name" class="js-form-required form-required">Username</label>
                <input autocorrect="none" autocapitalize="none" spellcheck="false" data-drupal-selector="edit-name" aria-describedby="edit-name--description" type="text"
                    id="edit-name" name="name" value="" size="60" maxlength="60" class="form-text required"
                    required="required" aria-required="true">
                <div id="edit-name--description" class="description">
                    Enter your Red Hat Developer username.
                </div>
            </div>
            <div
                class="js-form-item form-item js-form-type-password form-type-password js-form-item-pass form-item-pass">
                <label for="edit-pass" class="js-form-required form-required">Password</label>
                <input data-drupal-selector="edit-pass" aria-describedby="edit-pass--description" type="password"
                    id="edit-pass" name="pass" size="60" maxlength="128" class="form-text required" required="required"
                    aria-required="true">
                <div id="edit-pass--description" class="description">
                    Enter the password that accompanies your username.
                </div>
            </div>
            <input autocomplete="off" data-drupal-selector="form-v4notopk-gncqfbb-xmpot-n-m9rxm-djoudkmbgxdm"
                type="hidden" name="form_build_id" value="form-v4notOpK-GnCQFbB_XMPoT_N-m9rxM_dJOudkmBgXDM">
            <input data-drupal-selector="edit-user-login-form" type="hidden" name="form_id" value="user_login_form">
            <div data-drupal-selector="edit-actions" class="form-actions js-form-wrapper form-wrapper"
                id="edit-actions"><input data-drupal-selector="edit-submit" type="submit" id="edit-submit" name="op"
                    value="Log in" class="button js-form-submit form-submit">
            </div>
        </form>
    </div>
</div>
