# less-min-mixins
A collection of LESS mixins that allow you to write all your css using only mixins

```less
.details-panel {
    .w-h(44.5%,100%);
    .pos-rel;
    .float-r;
    .pos-b;
    .ov-a;
    .ov-xh;
    .p(10px);

    .header {
        .m-b(5px);
        .p(0, 20px);
	    .h(46px);
	    .txt-c(@white);
        .txt-sb(16px);
        .txt-lh(44px);
        .bdr(2px, #3B4442);
        .bdr-r(6px);
	    .bg-grad(@gold, @orange);

        .btn-remove {
            &:hover {
		        .bg-none;
		        .txt-c(#C2090C);
            }
        }
        .node-icon { .m-t(-5px); }
    }
    .tab-content { .m-t(10px); }
}
```
