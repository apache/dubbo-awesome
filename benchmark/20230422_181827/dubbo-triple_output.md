# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.765 ops/ms
# Warmup Iteration   2: 4.279 ops/ms
# Warmup Iteration   3: 7.449 ops/ms
Iteration   1: 7.496 ops/ms
Iteration   2: 8.086 ops/ms
Iteration   3: 8.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.885 ±(99.9%) 6.149 ops/ms [Average]
  (min, avg, max) = (7.496, 7.885, 8.086), stdev = 0.337
  CI (99.9%): [1.736, 14.034] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.528 ops/ms
# Warmup Iteration   2: 6.708 ops/ms
# Warmup Iteration   3: 8.562 ops/ms
Iteration   1: 8.228 ops/ms
Iteration   2: 8.936 ops/ms
Iteration   3: 8.932 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.699 ±(99.9%) 7.432 ops/ms [Average]
  (min, avg, max) = (8.228, 8.699, 8.936), stdev = 0.407
  CI (99.9%): [1.266, 16.131] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.011 ops/ms
# Warmup Iteration   2: 6.260 ops/ms
# Warmup Iteration   3: 7.992 ops/ms
Iteration   1: 8.640 ops/ms
Iteration   2: 8.529 ops/ms
Iteration   3: 8.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.525 ±(99.9%) 2.136 ops/ms [Average]
  (min, avg, max) = (8.406, 8.525, 8.640), stdev = 0.117
  CI (99.9%): [6.389, 10.662] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.122 ops/ms
# Warmup Iteration   2: 5.423 ops/ms
# Warmup Iteration   3: 6.873 ops/ms
Iteration   1: 7.246 ops/ms
Iteration   2: 7.128 ops/ms
Iteration   3: 7.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.135 ±(99.9%) 1.972 ops/ms [Average]
  (min, avg, max) = (7.030, 7.135, 7.246), stdev = 0.108
  CI (99.9%): [5.163, 9.106] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 13.437 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.654 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.952 ±(99.9%) 0.013 ms/op
Iteration   1: 4.013 ±(99.9%) 0.004 ms/op
Iteration   2: 3.947 ±(99.9%) 0.014 ms/op
Iteration   3: 4.016 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.992 ±(99.9%) 0.713 ms/op [Average]
  (min, avg, max) = (3.947, 3.992, 4.016), stdev = 0.039
  CI (99.9%): [3.280, 4.705] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 12.611 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.431 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.781 ±(99.9%) 0.008 ms/op
Iteration   1: 3.716 ±(99.9%) 0.007 ms/op
Iteration   2: 3.761 ±(99.9%) 0.006 ms/op
Iteration   3: 3.905 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.794 ±(99.9%) 1.800 ms/op [Average]
  (min, avg, max) = (3.716, 3.794, 3.905), stdev = 0.099
  CI (99.9%): [1.994, 5.594] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.850 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.700 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.933 ±(99.9%) 0.004 ms/op
Iteration   1: 4.018 ±(99.9%) 0.008 ms/op
Iteration   2: 3.885 ±(99.9%) 0.010 ms/op
Iteration   3: 3.948 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.950 ±(99.9%) 1.208 ms/op [Average]
  (min, avg, max) = (3.885, 3.950, 4.018), stdev = 0.066
  CI (99.9%): [2.743, 5.158] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 13.362 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.064 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.515 ±(99.9%) 0.010 ms/op
Iteration   1: 4.586 ±(99.9%) 0.016 ms/op
Iteration   2: 4.534 ±(99.9%) 0.012 ms/op
Iteration   3: 4.593 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.571 ±(99.9%) 0.583 ms/op [Average]
  (min, avg, max) = (4.534, 4.571, 4.593), stdev = 0.032
  CI (99.9%): [3.988, 5.154] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 13.274 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 4.756 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.080 ±(99.9%) 0.017 ms/op
Iteration   1: 3.941 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.507 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.612 ms/op
                 createUser·p0.95:   4.932 ms/op
                 createUser·p0.99:   6.488 ms/op
                 createUser·p0.999:  24.371 ms/op
                 createUser·p0.9999: 29.422 ms/op
                 createUser·p1.00:   30.769 ms/op

Iteration   2: 3.938 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.849 ms/op
                 createUser·p0.50:   3.756 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   4.907 ms/op
                 createUser·p0.99:   6.889 ms/op
                 createUser·p0.999:  26.640 ms/op
                 createUser·p0.9999: 28.312 ms/op
                 createUser·p1.00:   29.688 ms/op

Iteration   3: 3.961 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.868 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.153 ms/op
                 createUser·p0.99:   7.447 ms/op
                 createUser·p0.999:  13.681 ms/op
                 createUser·p0.9999: 31.813 ms/op
                 createUser·p1.00:   32.211 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 242988
  mean =      3.947 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 401 
    [ 2.500,  5.000) = 230648 
    [ 5.000,  7.500) = 10149 
    [ 7.500, 10.000) = 1229 
    [10.000, 12.500) = 244 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 109 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.507 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     24.281 ms/op
     p(99.9900) =     30.586 ms/op
     p(99.9990) =     32.000 ms/op
     p(99.9999) =     32.211 ms/op
    p(100.0000) =     32.211 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.999 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.322 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.970 ±(99.9%) 0.014 ms/op
Iteration   1: 3.807 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.819 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   3.981 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   7.010 ms/op
                 existUser·p0.999:  25.166 ms/op
                 existUser·p0.9999: 28.340 ms/op
                 existUser·p1.00:   29.262 ms/op

Iteration   2: 3.751 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   2.025 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   3.953 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   6.631 ms/op
                 existUser·p0.999:  9.519 ms/op
                 existUser·p0.9999: 28.851 ms/op
                 existUser·p1.00:   29.229 ms/op

Iteration   3: 3.840 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.690 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.522 ms/op
                 existUser·p0.95:   5.054 ms/op
                 existUser·p0.99:   7.111 ms/op
                 existUser·p0.999:  25.883 ms/op
                 existUser·p0.9999: 29.775 ms/op
                 existUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 252752
  mean =      3.799 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1051 
    [ 2.500,  5.000) = 242870 
    [ 5.000,  7.500) = 7002 
    [ 7.500, 10.000) = 1452 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 141 

  Percentiles, ms/op:
      p(0.0000) =      1.690 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     24.773 ms/op
     p(99.9900) =     29.229 ms/op
     p(99.9990) =     29.915 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 12.291 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.255 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.030 ±(99.9%) 0.011 ms/op
Iteration   1: 4.108 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.786 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   6.406 ms/op
                 getUser·p0.99:   8.815 ms/op
                 getUser·p0.999:  22.057 ms/op
                 getUser·p0.9999: 31.097 ms/op
                 getUser·p1.00:   34.996 ms/op

Iteration   2: 3.751 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.903 ms/op
                 getUser·p0.50:   3.699 ms/op
                 getUser·p0.90:   4.182 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   6.357 ms/op
                 getUser·p0.999:  13.891 ms/op
                 getUser·p0.9999: 28.833 ms/op
                 getUser·p1.00:   29.688 ms/op

Iteration   3: 3.725 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.354 ms/op
                 getUser·p0.50:   3.621 ms/op
                 getUser·p0.90:   4.186 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.455 ms/op
                 getUser·p0.999:  25.494 ms/op
                 getUser·p0.9999: 28.491 ms/op
                 getUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 248953
  mean =      3.854 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 770 
    [ 2.500,  5.000) = 237817 
    [ 5.000,  7.500) = 6832 
    [ 7.500, 10.000) = 2781 
    [10.000, 12.500) = 327 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 68 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.354 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      8.086 ms/op
     p(99.9000) =     21.502 ms/op
     p(99.9900) =     29.691 ms/op
     p(99.9990) =     34.607 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 13.809 ±(99.9%) 0.206 ms/op
# Warmup Iteration   2: 6.052 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.888 ±(99.9%) 0.019 ms/op
Iteration   1: 4.678 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.716 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  26.694 ms/op
                 listUser·p0.9999: 29.649 ms/op
                 listUser·p1.00:   31.130 ms/op

Iteration   2: 4.250 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.997 ms/op
                 listUser·p0.50:   4.194 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   6.463 ms/op
                 listUser·p0.999:  16.634 ms/op
                 listUser·p0.9999: 20.349 ms/op
                 listUser·p1.00:   21.529 ms/op

Iteration   3: 4.562 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.408 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.704 ms/op
                 listUser·p0.99:   8.520 ms/op
                 listUser·p0.999:  24.216 ms/op
                 listUser·p0.9999: 29.130 ms/op
                 listUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 213686
  mean =      4.489 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 191774 
    [ 5.000,  7.500) = 18035 
    [ 7.500, 10.000) = 2887 
    [10.000, 12.500) = 400 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.716 ms/op
     p(50.0000) =      4.325 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      8.249 ms/op
     p(99.9000) =     24.084 ms/op
     p(99.9900) =     29.107 ms/op
     p(99.9990) =     30.526 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.885 ± 6.149  ops/ms
ClientPb.existUser                       thrpt       3   8.699 ± 7.432  ops/ms
ClientPb.getUser                         thrpt       3   8.525 ± 2.136  ops/ms
ClientPb.listUser                        thrpt       3   7.135 ± 1.972  ops/ms
ClientPb.createUser                       avgt       3   3.992 ± 0.713   ms/op
ClientPb.existUser                        avgt       3   3.794 ± 1.800   ms/op
ClientPb.getUser                          avgt       3   3.950 ± 1.208   ms/op
ClientPb.listUser                         avgt       3   4.571 ± 0.583   ms/op
ClientPb.createUser                     sample  242988   3.947 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.507           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.628           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.989           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.881           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.281           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.586           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.211           ms/op
ClientPb.existUser                      sample  252752   3.799 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.690           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.133           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.620           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.980           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.773           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.229           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.950           ms/op
ClientPb.getUser                        sample  248953   3.854 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.354           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.723           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.760           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.086           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.502           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.691           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.996           ms/op
ClientPb.listUser                       sample  213686   4.489 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.716           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.014           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.480           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.249           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.084           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.107           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.130           ms/op
