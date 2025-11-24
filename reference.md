# Reference
## Imdb
<details><summary><code>client.imdb.<a href="/src/api/resources/imdb/client/Client.ts">createMovie</a>({ ...params }) -> FernSampleApi.MovieId</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Add a movie to the database
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.imdb.createMovie({
    title: "title",
    rating: 1.1
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FernSampleApi.CreateMovieRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ImdbClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.imdb.<a href="/src/api/resources/imdb/client/Client.ts">getMovie</a>(id) -> FernSampleApi.Movie</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve a movie from the database based on the ID
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.imdb.getMovie("tt0111161");

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `FernSampleApi.MovieId` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ImdbClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>
