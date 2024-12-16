<script>
    import {IconHome} from "@tabler/icons-svelte";
    import {IconFriends} from "@tabler/icons-svelte";
    import {IconUser} from "@tabler/icons-svelte";
    import {IconBook} from "@tabler/icons-svelte";
    import {IconSquare1} from "@tabler/icons-svelte";
    import {IconSquare2} from "@tabler/icons-svelte";
    import {IconSquare3} from "@tabler/icons-svelte";
    import {IconRss} from "@tabler/icons-svelte";
    import {IconBook2} from "@tabler/icons-svelte";
    import {IconBrandFacebook} from "@tabler/icons-svelte";
    import {IconBrandInstagram} from "@tabler/icons-svelte";
    import {IconBrandYoutube} from "@tabler/icons-svelte";
    import Menu from "./Menu.svelte";
    import MenuItem from "./MenuItem.svelte";

</script>
<aside class="flex flex-col w-72 gap-10 self-start border border-zinc-800 p-5 rounded-md">
    <Menu titulo="Navegação">
        <MenuItem texto="Início" href="/">
            <IconHome size={20} />
        </MenuItem>
        <MenuItem texto="Personagens" href="/">
            <IconFriends size={20} />
        </MenuItem>
        <MenuItem texto="Autores" href="/autores">
            <IconUser size={20} />
        </MenuItem>
        <MenuItem texto="Séries" href="/">
            <IconBook size={20} />
        </MenuItem>
    </Menu>
    <Menu titulo="Principais Autores">
        <MenuItem texto="J.K. Rowling" href="/autores/j-k-rowling">
            <IconSquare1 size={20} />
        </MenuItem>
        <MenuItem texto="J.R.R. Tolkien" href="/autores/j-r-r-tolkien">
            <IconSquare2 size={20} />
        </MenuItem>
        <MenuItem texto="George R.R. Martin" href="/autores/george-r-r-martin">
            <IconSquare3 size={20} />
        </MenuItem>
    </Menu>
    <Menu titulo="Outras Categorias">
        <MenuItem texto="Últimas Notícias" href="/">
            <IconRss size={20} />
        </MenuItem>
        <MenuItem texto="Séries Populares" href="/">
            <IconBook2 size={20} />
        </MenuItem>
        <MenuItem texto="Facebook" href="/">
            <IconBrandFacebook size={20} />
        </MenuItem>
        <MenuItem texto="Instagram" href="/">
            <IconBrandInstagram size={20} />
        </MenuItem>
        <MenuItem texto="YouTube" href="/">
            <IconBrandYoutube size={20} />
        </MenuItem>
    </Menu>
</aside>