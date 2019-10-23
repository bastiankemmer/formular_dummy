<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col-12">
                <Header class="text-left" text="1. Persönliche Angaben zum Vertragspartner"></Header>
            </div>
        </div>
        <div class="row margin-top-sm">
            <div class="col-md-5 col-sm-6">
                <InputField label="Vorname" placeholder="Vorname eingeben"></InputField>
            </div>
            <div class="d-none d-md-block col-md-2">
            </div>
            <div class="col-md-5 col-sm-6 d-block">
                <InputField label="Nachname" placeholder="Nachname eingeben"></InputField>
            </div>
        </div>
        <div class="row">
            <div class="col-md-4 col-sm-4">
                <InputField label="Straße" placeholder="Straße eingeben"></InputField>
            </div>
            <div class="col-md-1 col-sm-2">
                <InputField label="Hausnummer" placeholder="Hnr."></InputField>
            </div>
            <div class="d-none d-md-block col-md-2">
            </div>
            <div class="col-md-5 col-sm-6 d-block">
                <InputField label="Postleitzahl" placeholder="PLZ eingeben" type="number"></InputField>
            </div>
        </div>
        <div class="row margin-top-sm">
            <div class="col-md-5 col-sm-6">
                <InputField label="Ort" placeholder="Ort eingeben"></InputField>
            </div>
            <div class="d-none d-md-block col-md-2">
            </div>
            <div class="col-md-5 col-sm-6 d-block">
                <InputField label="Land" value="Deutschland" disabled="true"></InputField>
            </div>
        </div>
        <div class="row">
            <div class="col-12">
                <Header class="text-left" text="2. Persönliche Angaben zum Vertragspartner"></Header>
            </div>
        </div>
        <div class="row margin-top-sm">
            <div class="col-md-5 col-sm-6">
                <InputField label="Vorname" placeholder="Vorname eingeben"></InputField>
            </div>
            <div class="d-none d-md-block col-md-2">
            </div>
            <div class="col-md-5 col-sm-6 d-block">
                <InputField label="Nachname" placeholder="Nachname eingeben"></InputField>
            </div>
        </div>
        <div class="row">
            <div class="col-md-4 col-sm-4">
                <InputField label="Straße" placeholder="Straße eingeben"></InputField>
            </div>
            <div class="col-md-1 col-sm-2">
                <InputField label="Hausnummer" placeholder="Hnr."></InputField>
            </div>
            <div class="d-none d-md-block col-md-2">
            </div>
            <div class="col-md-5 col-sm-6 d-block">
                <InputField label="Postleitzahl" placeholder="PLZ eingeben" type="number"></InputField>
            </div>
        </div>
        <div class="row margin-top-sm">
            <div class="col-md-5 col-sm-6">
                <InputField label="Ort" placeholder="Ort eingeben"></InputField>
            </div>
            <div class="d-none d-md-block col-md-2">
            </div>
            <div class="col-md-5 col-sm-6 d-block">
                <InputField label="Land" value="Deutschland" disabled="true"></InputField>
            </div>
        </div>
        <div class="row">
            <div class="col-12">
                <Header class="text-left" text="3. Persönliche Angaben zum Vertragspartner"></Header>
            </div>
        </div>
        <div class="row margin-top-sm">
            <div class="col-md-5 col-sm-6">
                <InputField label="Vorname" placeholder="Vorname eingeben"></InputField>
            </div>
            <div class="d-none d-md-block col-md-2">
            </div>
            <div class="col-md-5 col-sm-6 d-block">
                <InputField label="Nachname" placeholder="Nachname eingeben"></InputField>
            </div>
        </div>
        <div class="row">
            <div class="col-md-4 col-sm-4">
                <InputField label="Straße" placeholder="Straße eingeben"></InputField>
            </div>
            <div class="col-md-1 col-sm-2">
                <InputField label="Hausnummer" placeholder="Hnr."></InputField>
            </div>
            <div class="d-none d-md-block col-md-2">
            </div>
            <div class="col-md-5 col-sm-6 d-block">
                <InputField label="Postleitzahl" placeholder="PLZ eingeben" type="number"></InputField>
            </div>
        </div>
        <div class="row margin-top-sm">
            <div class="col-md-5 col-sm-6">
                <InputField label="Ort" placeholder="Ort eingeben"></InputField>
            </div>
            <div class="d-none d-md-block col-md-2">
            </div>
            <div class="col-md-5 col-sm-6 d-block">
                <InputField label="Land" value="Deutschland" disabled="true"></InputField>
            </div>
        </div>
    </div>
</template>

<script>
    import Header from "./Header"
    import InputField from "./InputField"

    export default {
        name: 'Formular',
        components: {
            Header,
            InputField
        },
        props: {
            msg: String
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    h3 {
        margin: 40px 0 0;
    }

    ul {
        list-style-type: none;
        padding: 0;
    }

    li {
        display: inline-block;
        margin: 0 10px;
    }

    a {
        color: #42b983;
    }

    .margin-top-sm {
        margin-top: 1em;
    }
</style>
