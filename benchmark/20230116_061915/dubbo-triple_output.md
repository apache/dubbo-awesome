# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.280 ops/ms
# Warmup Iteration   2: 3.391 ops/ms
# Warmup Iteration   3: 5.950 ops/ms
Iteration   1: 6.122 ops/ms
Iteration   2: 6.480 ops/ms
Iteration   3: 6.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.393 ±(99.9%) 4.367 ops/ms [Average]
  (min, avg, max) = (6.122, 6.393, 6.576), stdev = 0.239
  CI (99.9%): [2.026, 10.760] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.929 ops/ms
# Warmup Iteration   2: 6.105 ops/ms
# Warmup Iteration   3: 7.038 ops/ms
Iteration   1: 6.746 ops/ms
Iteration   2: 6.637 ops/ms
Iteration   3: 6.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.722 ±(99.9%) 1.381 ops/ms [Average]
  (min, avg, max) = (6.637, 6.722, 6.782), stdev = 0.076
  CI (99.9%): [5.341, 8.103] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.713 ops/ms
# Warmup Iteration   2: 5.415 ops/ms
# Warmup Iteration   3: 6.310 ops/ms
Iteration   1: 6.263 ops/ms
Iteration   2: 6.379 ops/ms
Iteration   3: 6.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.437 ±(99.9%) 3.818 ops/ms [Average]
  (min, avg, max) = (6.263, 6.437, 6.670), stdev = 0.209
  CI (99.9%): [2.619, 10.256] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.748 ops/ms
# Warmup Iteration   2: 4.516 ops/ms
# Warmup Iteration   3: 5.493 ops/ms
Iteration   1: 5.475 ops/ms
Iteration   2: 5.539 ops/ms
Iteration   3: 5.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.569 ±(99.9%) 2.049 ops/ms [Average]
  (min, avg, max) = (5.475, 5.569, 5.693), stdev = 0.112
  CI (99.9%): [3.520, 7.618] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 15.521 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 5.644 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.107 ±(99.9%) 0.010 ms/op
Iteration   1: 4.960 ±(99.9%) 0.007 ms/op
Iteration   2: 4.804 ±(99.9%) 0.013 ms/op
Iteration   3: 4.774 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.846 ±(99.9%) 1.819 ms/op [Average]
  (min, avg, max) = (4.774, 4.846, 4.960), stdev = 0.100
  CI (99.9%): [3.027, 6.665] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 14.551 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 5.226 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.784 ±(99.9%) 0.007 ms/op
Iteration   1: 4.634 ±(99.9%) 0.008 ms/op
Iteration   2: 4.625 ±(99.9%) 0.011 ms/op
Iteration   3: 4.657 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.639 ±(99.9%) 0.306 ms/op [Average]
  (min, avg, max) = (4.625, 4.639, 4.657), stdev = 0.017
  CI (99.9%): [4.332, 4.945] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 15.160 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.258 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.899 ±(99.9%) 0.009 ms/op
Iteration   1: 4.896 ±(99.9%) 0.010 ms/op
Iteration   2: 4.817 ±(99.9%) 0.010 ms/op
Iteration   3: 4.919 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.877 ±(99.9%) 0.973 ms/op [Average]
  (min, avg, max) = (4.817, 4.877, 4.919), stdev = 0.053
  CI (99.9%): [3.905, 5.850] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 16.821 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 7.088 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.685 ±(99.9%) 0.009 ms/op
Iteration   1: 5.309 ±(99.9%) 0.018 ms/op
Iteration   2: 5.503 ±(99.9%) 0.013 ms/op
Iteration   3: 5.552 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.455 ±(99.9%) 2.338 ms/op [Average]
  (min, avg, max) = (5.309, 5.455, 5.552), stdev = 0.128
  CI (99.9%): [3.117, 7.793] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 15.597 ±(99.9%) 0.248 ms/op
# Warmup Iteration   2: 5.798 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.192 ±(99.9%) 0.021 ms/op
Iteration   1: 4.856 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.204 ms/op
                 createUser·p0.50:   4.588 ms/op
                 createUser·p0.90:   5.816 ms/op
                 createUser·p0.95:   6.521 ms/op
                 createUser·p0.99:   10.033 ms/op
                 createUser·p0.999:  23.761 ms/op
                 createUser·p0.9999: 27.921 ms/op
                 createUser·p1.00:   28.246 ms/op

Iteration   2: 4.894 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.864 ms/op
                 createUser·p0.50:   4.620 ms/op
                 createUser·p0.90:   6.005 ms/op
                 createUser·p0.95:   6.922 ms/op
                 createUser·p0.99:   9.568 ms/op
                 createUser·p0.999:  19.559 ms/op
                 createUser·p0.9999: 27.326 ms/op
                 createUser·p1.00:   28.246 ms/op

Iteration   3: 4.907 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.195 ms/op
                 createUser·p0.50:   4.735 ms/op
                 createUser·p0.90:   5.808 ms/op
                 createUser·p0.95:   6.324 ms/op
                 createUser·p0.99:   8.815 ms/op
                 createUser·p0.999:  15.574 ms/op
                 createUser·p0.9999: 29.605 ms/op
                 createUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 196389
  mean =      4.885 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 135531 
    [ 5.000,  7.500) = 55250 
    [ 7.500, 10.000) = 3979 
    [10.000, 12.500) = 864 
    [12.500, 15.000) = 351 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.864 ms/op
     p(50.0000) =      4.653 ms/op
     p(90.0000) =      5.857 ms/op
     p(95.0000) =      6.627 ms/op
     p(99.0000) =      9.535 ms/op
     p(99.9000) =     23.411 ms/op
     p(99.9900) =     28.028 ms/op
     p(99.9990) =     29.852 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 15.179 ±(99.9%) 0.217 ms/op
# Warmup Iteration   2: 5.632 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.941 ±(99.9%) 0.016 ms/op
Iteration   1: 4.583 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.130 ms/op
                 existUser·p0.50:   4.358 ms/op
                 existUser·p0.90:   5.448 ms/op
                 existUser·p0.95:   6.283 ms/op
                 existUser·p0.99:   8.946 ms/op
                 existUser·p0.999:  14.422 ms/op
                 existUser·p0.9999: 25.728 ms/op
                 existUser·p1.00:   28.770 ms/op

Iteration   2: 4.543 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.663 ms/op
                 existUser·p0.50:   4.293 ms/op
                 existUser·p0.90:   5.366 ms/op
                 existUser·p0.95:   6.185 ms/op
                 existUser·p0.99:   8.864 ms/op
                 existUser·p0.999:  19.122 ms/op
                 existUser·p0.9999: 24.344 ms/op
                 existUser·p1.00:   26.345 ms/op

Iteration   3: 4.760 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.376 ms/op
                 existUser·p0.50:   4.473 ms/op
                 existUser·p0.90:   5.816 ms/op
                 existUser·p0.95:   6.726 ms/op
                 existUser·p0.99:   9.355 ms/op
                 existUser·p0.999:  15.891 ms/op
                 existUser·p0.9999: 31.501 ms/op
                 existUser·p1.00:   32.735 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 207316
  mean =      4.627 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 169589 
    [ 5.000,  7.500) = 32360 
    [ 7.500, 10.000) = 4057 
    [10.000, 12.500) = 825 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.663 ms/op
     p(50.0000) =      4.375 ms/op
     p(90.0000) =      5.538 ms/op
     p(95.0000) =      6.398 ms/op
     p(99.0000) =      9.060 ms/op
     p(99.9000) =     16.739 ms/op
     p(99.9900) =     30.254 ms/op
     p(99.9990) =     32.007 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 15.967 ±(99.9%) 0.218 ms/op
# Warmup Iteration   2: 5.620 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.094 ±(99.9%) 0.020 ms/op
Iteration   1: 5.027 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.765 ms/op
                 getUser·p0.50:   4.751 ms/op
                 getUser·p0.90:   6.099 ms/op
                 getUser·p0.95:   7.422 ms/op
                 getUser·p0.99:   10.034 ms/op
                 getUser·p0.999:  16.810 ms/op
                 getUser·p0.9999: 29.780 ms/op
                 getUser·p1.00:   30.409 ms/op

Iteration   2: 5.109 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.224 ms/op
                 getUser·p0.50:   4.669 ms/op
                 getUser·p0.90:   6.681 ms/op
                 getUser·p0.95:   7.987 ms/op
                 getUser·p0.99:   10.879 ms/op
                 getUser·p0.999:  25.170 ms/op
                 getUser·p0.9999: 37.304 ms/op
                 getUser·p1.00:   38.797 ms/op

Iteration   3: 4.917 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.138 ms/op
                 getUser·p0.50:   4.710 ms/op
                 getUser·p0.90:   5.620 ms/op
                 getUser·p0.95:   6.406 ms/op
                 getUser·p0.99:   9.683 ms/op
                 getUser·p0.999:  15.867 ms/op
                 getUser·p0.9999: 33.309 ms/op
                 getUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 191266
  mean =      5.016 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 128319 
    [ 5.000,  7.500) = 53515 
    [ 7.500, 10.000) = 7270 
    [10.000, 12.500) = 1471 
    [12.500, 15.000) = 403 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.765 ms/op
     p(50.0000) =      4.710 ms/op
     p(90.0000) =      6.070 ms/op
     p(95.0000) =      7.463 ms/op
     p(99.0000) =     10.224 ms/op
     p(99.9000) =     16.810 ms/op
     p(99.9900) =     33.411 ms/op
     p(99.9990) =     38.498 ms/op
     p(99.9999) =     38.797 ms/op
    p(100.0000) =     38.797 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.237 ±(99.9%) 0.330 ms/op
# Warmup Iteration   2: 6.842 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.518 ±(99.9%) 0.020 ms/op
Iteration   1: 5.909 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.609 ms/op
                 listUser·p0.50:   5.554 ms/op
                 listUser·p0.90:   7.037 ms/op
                 listUser·p0.95:   8.831 ms/op
                 listUser·p0.99:   11.960 ms/op
                 listUser·p0.999:  24.375 ms/op
                 listUser·p0.9999: 26.848 ms/op
                 listUser·p1.00:   28.246 ms/op

Iteration   2: 5.709 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   0.889 ms/op
                 listUser·p0.50:   5.333 ms/op
                 listUser·p0.90:   6.930 ms/op
                 listUser·p0.95:   8.253 ms/op
                 listUser·p0.99:   11.583 ms/op
                 listUser·p0.999:  25.658 ms/op
                 listUser·p0.9999: 30.625 ms/op
                 listUser·p1.00:   37.093 ms/op

Iteration   3: 5.940 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.765 ms/op
                 listUser·p0.50:   5.636 ms/op
                 listUser·p0.90:   6.963 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   11.941 ms/op
                 listUser·p0.999:  22.151 ms/op
                 listUser·p0.9999: 25.809 ms/op
                 listUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 163938
  mean =      5.851 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 28172 
    [ 5.000,  7.500) = 123482 
    [ 7.500, 10.000) = 8327 
    [10.000, 12.500) = 2616 
    [12.500, 15.000) = 727 
    [15.000, 17.500) = 242 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      5.513 ms/op
     p(90.0000) =      6.963 ms/op
     p(95.0000) =      8.487 ms/op
     p(99.0000) =     11.846 ms/op
     p(99.9000) =     23.822 ms/op
     p(99.9900) =     29.878 ms/op
     p(99.9990) =     33.657 ms/op
     p(99.9999) =     37.093 ms/op
    p(100.0000) =     37.093 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.393 ± 4.367  ops/ms
ClientPb.existUser                       thrpt       3   6.722 ± 1.381  ops/ms
ClientPb.getUser                         thrpt       3   6.437 ± 3.818  ops/ms
ClientPb.listUser                        thrpt       3   5.569 ± 2.049  ops/ms
ClientPb.createUser                       avgt       3   4.846 ± 1.819   ms/op
ClientPb.existUser                        avgt       3   4.639 ± 0.306   ms/op
ClientPb.getUser                          avgt       3   4.877 ± 0.973   ms/op
ClientPb.listUser                         avgt       3   5.455 ± 2.338   ms/op
ClientPb.createUser                     sample  196389   4.885 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.864           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.653           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.857           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.627           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.535           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.411           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.028           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.736           ms/op
ClientPb.existUser                      sample  207316   4.627 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.663           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.375           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.538           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.398           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.060           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.739           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.254           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.735           ms/op
ClientPb.getUser                        sample  191266   5.016 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.765           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.710           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.070           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.463           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.224           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.810           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.411           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.797           ms/op
ClientPb.listUser                       sample  163938   5.851 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.889           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.963           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.487           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.846           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.822           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.878           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.093           ms/op
