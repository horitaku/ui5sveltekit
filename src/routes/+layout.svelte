<script lang="ts">
import "@ui5/webcomponents/dist/Avatar";
import "@ui5/webcomponents/dist/Button";
import "@ui5/webcomponents-fiori/dist/ShellBar";
import "@ui5/webcomponents-icons/dist/customer";
import "@ui5/webcomponents-icons/dist/nav-back";
</script>
<ui5-shellbar primary-title="Corporate Portal" secondary-title="Secondary title">
    <ui5-avatar slot="profile" icon="customer"></ui5-avatar>
    <img slot="logo" src="https://sap.github.io/ui5-webcomponents/images/sap-logo-svg.svg" />
    <ui5-button icon="nav-back" slot="startButton"></ui5-button>
</ui5-shellbar>
<slot></slot>