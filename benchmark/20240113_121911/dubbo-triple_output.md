# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.869 ops/ms
# Warmup Iteration   2: 12.191 ops/ms
# Warmup Iteration   3: 12.461 ops/ms
Iteration   1: 12.606 ops/ms
Iteration   2: 12.713 ops/ms
Iteration   3: 12.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.661 ±(99.9%) 0.975 ops/ms [Average]
  (min, avg, max) = (12.606, 12.661, 12.713), stdev = 0.053
  CI (99.9%): [11.686, 13.637] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.451 ops/ms
# Warmup Iteration   2: 13.363 ops/ms
# Warmup Iteration   3: 13.297 ops/ms
Iteration   1: 13.246 ops/ms
Iteration   2: 13.228 ops/ms
Iteration   3: 13.258 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.244 ±(99.9%) 0.277 ops/ms [Average]
  (min, avg, max) = (13.228, 13.244, 13.258), stdev = 0.015
  CI (99.9%): [12.967, 13.521] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.836 ops/ms
# Warmup Iteration   2: 12.421 ops/ms
# Warmup Iteration   3: 12.880 ops/ms
Iteration   1: 12.978 ops/ms
Iteration   2: 12.868 ops/ms
Iteration   3: 12.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.858 ±(99.9%) 2.291 ops/ms [Average]
  (min, avg, max) = (12.727, 12.858, 12.978), stdev = 0.126
  CI (99.9%): [10.567, 15.149] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.648 ops/ms
# Warmup Iteration   2: 10.435 ops/ms
# Warmup Iteration   3: 10.590 ops/ms
Iteration   1: 10.652 ops/ms
Iteration   2: 10.581 ops/ms
Iteration   3: 10.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.627 ±(99.9%) 0.736 ops/ms [Average]
  (min, avg, max) = (10.581, 10.627, 10.652), stdev = 0.040
  CI (99.9%): [9.891, 11.363] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.989 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.634 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.004 ms/op
Iteration   1: 2.527 ±(99.9%) 0.004 ms/op
Iteration   2: 2.528 ±(99.9%) 0.004 ms/op
Iteration   3: 2.530 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.528 ±(99.9%) 0.028 ms/op [Average]
  (min, avg, max) = (2.527, 2.528, 2.530), stdev = 0.002
  CI (99.9%): [2.500, 2.556] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.647 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.433 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.376 ±(99.9%) 0.004 ms/op
Iteration   1: 2.405 ±(99.9%) 0.003 ms/op
Iteration   2: 2.432 ±(99.9%) 0.004 ms/op
Iteration   3: 2.423 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.420 ±(99.9%) 0.246 ms/op [Average]
  (min, avg, max) = (2.405, 2.420, 2.432), stdev = 0.013
  CI (99.9%): [2.174, 2.666] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.811 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
Iteration   1: 2.460 ±(99.9%) 0.004 ms/op
Iteration   2: 2.493 ±(99.9%) 0.003 ms/op
Iteration   3: 2.460 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.471 ±(99.9%) 0.348 ms/op [Average]
  (min, avg, max) = (2.460, 2.471, 2.493), stdev = 0.019
  CI (99.9%): [2.123, 2.820] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.507 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.004 ms/op
Iteration   1: 3.003 ±(99.9%) 0.006 ms/op
Iteration   2: 2.975 ±(99.9%) 0.004 ms/op
Iteration   3: 2.984 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.987 ±(99.9%) 0.262 ms/op [Average]
  (min, avg, max) = (2.975, 2.987, 3.003), stdev = 0.014
  CI (99.9%): [2.725, 3.250] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 3.990 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.703 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.005 ms/op
Iteration   1: 2.562 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.893 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   4.104 ms/op
                 createUser·p0.999:  10.915 ms/op
                 createUser·p0.9999: 14.705 ms/op
                 createUser·p1.00:   15.172 ms/op

Iteration   2: 2.553 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.998 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  9.614 ms/op
                 createUser·p0.9999: 12.272 ms/op
                 createUser·p1.00:   12.894 ms/op

Iteration   3: 2.547 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.813 ms/op
                 createUser·p0.999:  8.365 ms/op
                 createUser·p0.9999: 11.784 ms/op
                 createUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375474
  mean =      2.554 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 179339 
    [ 2.500,  3.750) = 191185 
    [ 3.750,  5.000) = 4037 
    [ 5.000,  6.250) = 425 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.912 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     14.229 ms/op
     p(99.9990) =     15.007 ms/op
     p(99.9999) =     15.172 ms/op
    p(100.0000) =     15.172 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.701 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.422 ±(99.9%) 0.005 ms/op
Iteration   1: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  6.714 ms/op
                 existUser·p0.9999: 13.662 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   2: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.989 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  6.753 ms/op
                 existUser·p0.9999: 12.564 ms/op
                 existUser·p1.00:   13.271 ms/op

Iteration   3: 2.417 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.087 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  6.292 ms/op
                 existUser·p0.9999: 12.240 ms/op
                 existUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395085
  mean =      2.428 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 199008 
    [ 2.500,  3.750) = 193087 
    [ 3.750,  5.000) = 2192 
    [ 5.000,  6.250) = 326 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.985 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      2.945 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.555 ms/op
     p(99.9000) =      6.496 ms/op
     p(99.9900) =     13.099 ms/op
     p(99.9990) =     13.799 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.867 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.584 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.006 ms/op
Iteration   1: 2.502 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.620 ms/op
                 getUser·p0.50:   2.521 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.543 ms/op
                 getUser·p0.999:  11.168 ms/op
                 getUser·p0.9999: 13.730 ms/op
                 getUser·p1.00:   14.303 ms/op

Iteration   2: 2.526 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.961 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.920 ms/op
                 getUser·p0.999:  7.432 ms/op
                 getUser·p0.9999: 11.824 ms/op
                 getUser·p1.00:   12.780 ms/op

Iteration   3: 2.518 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.907 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.887 ms/op
                 getUser·p0.999:  8.684 ms/op
                 getUser·p0.9999: 12.337 ms/op
                 getUser·p1.00:   13.271 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381351
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 188521 
    [ 2.500,  3.750) = 188714 
    [ 3.750,  5.000) = 3065 
    [ 5.000,  6.250) = 532 
    [ 6.250,  7.500) = 102 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.620 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      7.447 ms/op
     p(99.9900) =     13.416 ms/op
     p(99.9990) =     13.949 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.919 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.028 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.009 ms/op
Iteration   1: 2.970 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.760 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.077 ms/op
                 listUser·p0.9999: 10.420 ms/op
                 listUser·p1.00:   10.846 ms/op

Iteration   2: 2.977 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.895 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 12.142 ms/op
                 listUser·p1.00:   16.155 ms/op

Iteration   3: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.986 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.290 ms/op
                 listUser·p0.9999: 11.634 ms/op
                 listUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322040
  mean =      2.978 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 162 
    [ 1.250,  2.500) = 98076 
    [ 2.500,  3.750) = 186988 
    [ 3.750,  5.000) = 29919 
    [ 5.000,  6.250) = 5773 
    [ 6.250,  7.500) = 506 
    [ 7.500,  8.750) = 202 
    [ 8.750, 10.000) = 197 
    [10.000, 11.250) = 147 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      9.208 ms/op
     p(99.9900) =     11.665 ms/op
     p(99.9990) =     14.731 ms/op
     p(99.9999) =     16.155 ms/op
    p(100.0000) =     16.155 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.661 ± 0.975  ops/ms
ClientPb.existUser                       thrpt       3  13.244 ± 0.277  ops/ms
ClientPb.getUser                         thrpt       3  12.858 ± 2.291  ops/ms
ClientPb.listUser                        thrpt       3  10.627 ± 0.736  ops/ms
ClientPb.createUser                       avgt       3   2.528 ± 0.028   ms/op
ClientPb.existUser                        avgt       3   2.420 ± 0.246   ms/op
ClientPb.getUser                          avgt       3   2.471 ± 0.348   ms/op
ClientPb.listUser                         avgt       3   2.987 ± 0.262   ms/op
ClientPb.createUser                     sample  375474   2.554 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.893           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.471           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.229           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.172           ms/op
ClientPb.existUser                      sample  395085   2.428 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.985           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.486           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.945           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.555           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.496           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.099           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.254           ms/op
ClientPb.getUser                        sample  381351   2.515 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.620           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.789           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.447           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.416           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.303           ms/op
ClientPb.listUser                       sample  322040   2.978 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.760           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.208           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.665           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.155           ms/op
