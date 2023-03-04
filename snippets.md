```html
<section>
      <div class="container">
        <div class="columns">
          <div class="column is-10 is-offset-1">
            <nav class="panel">
              <p class="panel-heading">
                Repositories
              </p>
              <div class="panel-block">
                <p class="control has-icons-left">
                  <input class="input" type="text" placeholder="Search">
                  <span class="icon is-left">
                    <i class="fas fa-search" aria-hidden="true"></i>
                  </span>
                </p>
              </div>
              <p class="panel-tabs">
                <a class="is-active">All</a>
                <a>Public</a>
                <a>Private</a>
                <a>Sources</a>
                <a>Forks</a>
              </p>
              <a class="panel-block is-active">
                <span class="panel-icon">
                  <i class="fas fa-book" aria-hidden="true"></i>
                </span>
                bulma
              </a>
              <a class="panel-block">
                <span class="panel-icon">
                  <i class="fas fa-book" aria-hidden="true"></i>
                </span>
                marksheet
              </a>
              <a class="panel-block">
                <span class="panel-icon">
                  <i class="fas fa-book" aria-hidden="true"></i>
                </span>
                minireset.css
              </a>
              <a class="panel-block">
                <span class="panel-icon">
                  <i class="fas fa-book" aria-hidden="true"></i>
                </span>
                jgthms.github.io
              </a>
              <a class="panel-block">
                <span class="panel-icon">
                  <i class="fas fa-code-branch" aria-hidden="true"></i>
                </span>
                daniellowtw/infboard
              </a>
              <a class="panel-block">
                <span class="panel-icon">
                  <i class="fas fa-code-branch" aria-hidden="true"></i>
                </span>
                mojs
              </a>
              <label class="panel-block">
                <input type="checkbox">
                remember me
              </label>
              <div class="panel-block">
                <button class="button is-link is-outlined is-fullwidth">
                  Reset all filters
                </button>
              </div>
            </nav>
          </div>
        </div>
      </div>
     </section>
```
# Text

```html
<section>
      <div class="container">
        <div class="columns">
          <div class="column is-10 is-offset-1 is-offset-1-mobile">
            I am a MSc student at the Department of Computer Science, ETH Zürich
            <div class="content box">
              <h1>Hello World</h1>
              <p>Lorem ipsum<sup><a>[1]</a></sup> dolor sit amet, consectetur adipiscing elit. Nulla accumsan, metus ultrices eleifend gravida, nulla nunc varius lectus, nec rutrum justo nibh eu lectus. Ut vulputate semper dui. Fusce erat odio, sollicitudin vel erat vel, interdum mattis neque. Sub<sub>script</sub> works as well!</p>
              <h2>Second level</h2>
              <p>Curabitur accumsan turpis pharetra <strong>augue tincidunt</strong> blandit. Quisque condimentum maximus mi, sit amet commodo arcu rutrum id. Proin pretium urna vel cursus venenatis. Suspendisse potenti. Etiam mattis sem rhoncus lacus dapibus facilisis. Donec at dignissim dui. Ut et neque nisl.</p>
              <ul>
                <li>In fermentum leo eu lectus mollis, quis dictum mi aliquet.</li>
                <li>Morbi eu nulla lobortis, lobortis est in, fringilla felis.</li>
                <li>Aliquam nec felis in sapien venenatis viverra fermentum nec lectus.</li>
                <li>Ut non enim metus.</li>
              </ul>
              <h3>Third level</h3>
              <p>Quisque ante lacus, malesuada ac auctor vitae, congue <a href="#">non ante</a>. Phasellus lacus ex, semper ac tortor nec, fringilla condimentum orci. Fusce eu rutrum tellus.</p>
              <ol>
                <li>Donec blandit a lorem id convallis.</li>
                <li>Cras gravida arcu at diam gravida gravida.</li>
                <li>Integer in volutpat libero.</li>
                <li>Donec a diam tellus.</li>
                <li>Aenean nec tortor orci.</li>
                <li>Quisque aliquam cursus urna, non bibendum massa viverra eget.</li>
                <li>Vivamus maximus ultricies pulvinar.</li>
              </ol>
              <blockquote>Ut venenatis, nisl scelerisque sollicitudin fermentum, quam libero hendrerit ipsum, ut blandit est tellus sit amet turpis.</blockquote>
              <p>Quisque at semper enim, eu hendrerit odio. Etiam auctor nisl et <em>justo sodales</em> elementum. Maecenas ultrices lacus quis neque consectetur, et lobortis nisi molestie.</p>
              <p>Sed sagittis enim ac tortor maximus rutrum. Nulla facilisi. Donec mattis vulputate risus in luctus. Maecenas vestibulum interdum commodo.</p>
              <dl>
                <dt>Web</dt>
                <dd>The part of the Internet that contains websites and web pages</dd>
                <dt>HTML</dt>
                <dd>A markup language for creating web pages</dd>
                <dt>CSS</dt>
                <dd>A technology to make HTML look better</dd>
              </dl>
              <p>Suspendisse egestas sapien non felis placerat elementum. Morbi tortor nisl, suscipit sed mi sit amet, mollis malesuada nulla. Nulla facilisi. Nullam ac erat ante.</p>
              <h4>Fourth level</h4>
              <p>Nulla efficitur eleifend nisi, sit amet bibendum sapien fringilla ac. Mauris euismod metus a tellus laoreet, at elementum ex efficitur.</p>
              <pre>
            &lt;!DOCTYPE html&gt;
            &lt;html&gt;
              &lt;head&gt;
                &lt;title&gt;Hello World&lt;/title&gt;
              &lt;/head&gt;
              &lt;body&gt;
                &lt;p&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec viverra nec nulla vitae mollis.&lt;/p&gt;
              &lt;/body&gt;
            &lt;/html&gt;
            </pre>
              <p>Maecenas eleifend sollicitudin dui, faucibus sollicitudin augue cursus non. Ut finibus eleifend arcu ut vehicula. Mauris eu est maximus est porta condimentum in eu justo. Nulla id iaculis sapien.</p>
              <table>
                <thead>
                  <tr>
                    <th>One</th>
                    <th>Two</th>
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <td>Three</td>
                    <td>Four</td>
                  </tr>
                  <tr>
                    <td>Five</td>
                    <td>Six</td>
                  </tr>
                  <tr>
                    <td>Seven</td>
                    <td>Eight</td>
                  </tr>
                  <tr>
                    <td>Nine</td>
                    <td>Ten</td>
                  </tr>
                  <tr>
                    <td>Eleven</td>
                    <td>Twelve</td>
                  </tr>
                </tbody>
              </table>
              <p>Phasellus porttitor enim id metus volutpat ultricies. Ut nisi nunc, blandit sed dapibus at, vestibulum in felis. Etiam iaculis lorem ac nibh bibendum rhoncus. Nam interdum efficitur ligula sit amet ullamcorper. Etiam tristique, leo vitae porta faucibus, mi lacus laoreet metus, at cursus leo est vel tellus. Sed ac posuere est. Nunc ultricies nunc neque, vitae ultricies ex sodales quis. Aliquam eu nibh in libero accumsan pulvinar. Nullam nec nisl placerat, pretium metus vel, euismod ipsum. Proin tempor cursus nisl vel condimentum. Nam pharetra varius metus non pellentesque.</p>
              <h5>Fifth level</h5>
              <p>Aliquam sagittis rhoncus vulputate. Cras non luctus sem, sed tincidunt ligula. Vestibulum at nunc elit. Praesent aliquet ligula mi, in luctus elit volutpat porta. Phasellus molestie diam vel nisi sodales, a eleifend augue laoreet. Sed nec eleifend justo. Nam et sollicitudin odio.</p>
              <figure>
                <img src="https://bulma.io/images/placeholders/256x256.png">
                <img src="https://bulma.io/images/placeholders/256x256.png">
                <figcaption>
                  Figure 1: Some beautiful placeholders
                </figcaption>
              </figure>
              <h6>Sixth level</h6>
              <p>Cras in nibh lacinia, venenatis nisi et, auctor urna. Donec pulvinar lacus sed diam dignissim, ut eleifend eros accumsan. Phasellus non tortor eros. Ut sed rutrum lacus. Etiam purus nunc, scelerisque quis enim vitae, malesuada ultrices turpis. Nunc vitae maximus purus, nec consectetur dui. Suspendisse euismod, elit vel rutrum commodo, ipsum tortor maximus dui, sed varius sapien odio vitae est. Etiam at cursus metus.</p>
            </div>
          </div>
        </div>
      </div>
     </section>
```


# Timeline based work ex
```html

     <section>
      <div class="container">
        <div class="columns">
          <div class="column is-11 is-offset-0 is-offset-1-mobile is-10-mobile">
            <div class="content">
            <h4 class="title">Work Experience</h4>
            <div class="timeline">
              <div class="timeline-item">
                <div class="timeline-marker">
                  <!-- <i class="fa fa-flag"></i> -->
                </div>
                <div class="timeline-content">
                  <p class="heading">October 2020 - September 2021</p>
                  <div class="box">
                    <p><span class="has-text-weight-medium" >Oracle India Private Limited - Oracle Cloud AI Services (OCAS); </span> <span class="has-text-weight-medium">Bengaluru, India</span><br/><span class="is-italic">Member of Technical Staff;</span><span class="is-italic"> October 2020 - September 2021</span></p>
                  <p class="has-text-weight-normal is-size-6">
                    In this role at OCAS, I worked on end-to-end experimentation with deep learning models for NLP, making them production
                    ready and implementing APIs to expose them as cloud services.</p>
                  
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      </div>
      </section>
```