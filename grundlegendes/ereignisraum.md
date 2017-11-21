 Ereignisraum (sample space)
 ===
 
 #### Vereinigung 

<script async src="//jsfiddle.net/endsub/daonn1vw/embed/result,js/"></script>

<script>
const Dropdown = require('gitbook-styleguide/lib/Dropdown')
<Dropdown>
    <Button>
        Toggle dropdown <Button.Caret />
    </Button>
    <Dropdown.Item header>Account</Dropdown.Item>
    <Dropdown.Item href="/profile">Profile</Dropdown.Item>
    <Dropdown.Item href="/settings">Settings</Dropdown.Item>
    <Dropdown.Divider />
    <Dropdown.Item onClick={e => alert('Logout')}>Logout</Dropdown.Item>
</Dropdown>
</script>