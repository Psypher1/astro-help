// {articles.map(article =>{
// let postYear = article.published_at.slice(0, 4)
// if (currentYear !== postYear){
// currentYear = postYear

// if ( currentYear === postYear ){

// return <div>
// <article>
// <h2>{article.title}</h2>
// <date> {formatDate(article.published_at)}</date>
// </article>
// </div>  
// }
// }

// })}

// <article class="flex flex-col gap-4 border border-gray-500 p-4 rounded ">
// <img src={article.cover_image} class="w-98 h-48" alt={article.title}>
// <div>
// <a href={`articles/${article.slug}`} class="text-2xl font-semibold hover:text-gray-300">{article.title}</a>
// <p class="prose text-gray-400 mb-4">{article.description}</p>

// <div class="flex items-center gap-3">
// {article.tag_list.map(tag => (
// <a href='/' class="text-sm rounded block px-2 py-2 bg-gray-800">#{tag}</a>
// ))}  
// </div>
// </div>
// </article>
