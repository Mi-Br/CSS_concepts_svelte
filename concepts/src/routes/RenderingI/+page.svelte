
<!-- <h1>Title</h1> -->
<div class="section">
    <div class="subject">
        <div class="title">Built in declarations and inheritance</div>
    </div>
    <div class="content">
        <h2>Inheritance </h2>
        <p>Some properties automatically inherit values from parent while others - do not. For instance, typography related properties are inheritable. But other properties, such as border are not.</p>
        <code>
            {`
                function () {
                return {
                    color: 'red',
                    fontSize: '2rem',
                    border: '1px solid black'
                }
            `
            }
        </code>
        
        <!-- <div class="code">Some code goes here</div> -->
    </div>
</div>

<style>
    * {outline: 1px solid pink;}
    .section {
        height: 100vh;
        width: 100vw;
        display:grid;
        grid-template-columns: 300px 1fr;
    }
    .subject {
        background-color: #eee;
        position: relative;
    }
    .content {
        background-color: #ddd;
        padding-inline: 1rem;
    }
    .title {
        font-size: 2rem;
        font-weight: bold;
        padding: 1rem;
        position: sticky;line-height: 1.2;
        /* top: 100px; */
    }
    h2 {
        font-size: 2rem;
        font-weight: bold;
        padding: 1rem;
    }
    code {
        display: inline-block;
        outline: 1px solid pink;
        background-color: #eee;
        padding: 2rem;
    }
    textarea{
        padding: .1em;
    }
    .code_sample {
        display: grid;
        grid-template-columns: 1fr 1fr;
    }
   
</style>