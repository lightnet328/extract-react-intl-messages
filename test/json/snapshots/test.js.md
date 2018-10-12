# Snapshot report for `test/json/test.js`

The actual snapshot is saved in `test.js.snap`.

Generated by [AVA](https://ava.li).

## delimiter - nest

> Snapshot 1

    {
      'a.hello': 'hello',
      'a.world': 'world',
      'b.hello': 'hello',
      'b.world': 'world',
    }

> Snapshot 2

    {
      'a.hello': '',
      'a.world': '',
      'b.hello': '',
      'b.world': '',
    }

## export json

> Snapshot 1

    {
      'a.hello': 'hello',
      'a.world': 'world',
      'b.hello': 'hello',
      'b.world': 'world',
    }

> Snapshot 2

    {
      'a.hello': '',
      'a.world': '',
      'b.hello': '',
      'b.world': '',
    }

## export json - nest

> Snapshot 1

    {
      a: {
        hello: 'hello',
        world: 'world',
      },
      b: {
        hello: 'hello',
        world: 'world',
      },
    }

> Snapshot 2

    {
      a: {
        hello: '',
        world: '',
      },
      b: {
        hello: '',
        world: '',
      },
    }

## export json with removed messages

> Snapshot 1

    {
      'a.hello': 'hello',
      'a.world': 'world',
      'b.hello': 'hello',
      'b.world': 'world',
    }

> Snapshot 2

    {
      'a.hello': '',
      'a.world': '',
      'b.hello': '',
      'b.world': '',
    }

> Snapshot 3

    {
      'a.hello': 'hello',
      'b.hello': 'hello',
      'b.world': 'world',
    }

> Snapshot 4

    {
      'a.hello': '',
      'b.hello': '',
      'b.world': '',
    }

## sort keys

> Snapshot 1

    [
      'a.hello',
      'a.world',
      'b.hello',
      'b.world',
      'c.hello',
      'y.hello',
      'z.hello',
    ]

> Snapshot 2

    [
      'a.hello',
      'a.world',
      'b.hello',
      'b.world',
      'c.hello',
      'y.hello',
      'z.hello',
    ]