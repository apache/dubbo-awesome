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
# Warmup Iteration   1: 2.262 ops/ms
# Warmup Iteration   2: 4.999 ops/ms
# Warmup Iteration   3: 8.384 ops/ms
Iteration   1: 9.262 ops/ms
Iteration   2: 9.345 ops/ms
Iteration   3: 9.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.439 ±(99.9%) 4.346 ops/ms [Average]
  (min, avg, max) = (9.262, 9.439, 9.710), stdev = 0.238
  CI (99.9%): [5.093, 13.785] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.344 ops/ms
# Warmup Iteration   2: 8.839 ops/ms
# Warmup Iteration   3: 9.461 ops/ms
Iteration   1: 9.825 ops/ms
Iteration   2: 9.864 ops/ms
Iteration   3: 9.520 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.736 ±(99.9%) 3.433 ops/ms [Average]
  (min, avg, max) = (9.520, 9.736, 9.864), stdev = 0.188
  CI (99.9%): [6.303, 13.170] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.756 ops/ms
# Warmup Iteration   2: 8.378 ops/ms
# Warmup Iteration   3: 9.295 ops/ms
Iteration   1: 9.152 ops/ms
Iteration   2: 9.579 ops/ms
Iteration   3: 9.322 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.351 ±(99.9%) 3.921 ops/ms [Average]
  (min, avg, max) = (9.152, 9.351, 9.579), stdev = 0.215
  CI (99.9%): [5.430, 13.272] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.923 ops/ms
# Warmup Iteration   2: 7.366 ops/ms
# Warmup Iteration   3: 7.955 ops/ms
Iteration   1: 7.823 ops/ms
Iteration   2: 7.919 ops/ms
Iteration   3: 7.943 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.895 ±(99.9%) 1.161 ops/ms [Average]
  (min, avg, max) = (7.823, 7.895, 7.943), stdev = 0.064
  CI (99.9%): [6.734, 9.056] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.940 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.935 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.525 ±(99.9%) 0.010 ms/op
Iteration   1: 3.363 ±(99.9%) 0.010 ms/op
Iteration   2: 3.283 ±(99.9%) 0.010 ms/op
Iteration   3: 3.191 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.279 ±(99.9%) 1.574 ms/op [Average]
  (min, avg, max) = (3.191, 3.279, 3.363), stdev = 0.086
  CI (99.9%): [1.705, 4.852] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.090 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.479 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.313 ±(99.9%) 0.010 ms/op
Iteration   1: 3.242 ±(99.9%) 0.008 ms/op
Iteration   2: 3.289 ±(99.9%) 0.008 ms/op
Iteration   3: 3.308 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.280 ±(99.9%) 0.613 ms/op [Average]
  (min, avg, max) = (3.242, 3.280, 3.308), stdev = 0.034
  CI (99.9%): [2.667, 3.892] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.882 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.753 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.695 ±(99.9%) 0.004 ms/op
Iteration   1: 3.324 ±(99.9%) 0.006 ms/op
Iteration   2: 3.385 ±(99.9%) 0.005 ms/op
Iteration   3: 3.431 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.380 ±(99.9%) 0.977 ms/op [Average]
  (min, avg, max) = (3.324, 3.380, 3.431), stdev = 0.054
  CI (99.9%): [2.403, 4.357] (assumes normal distribution)


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
# Warmup Iteration   1: 11.262 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.403 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.985 ±(99.9%) 0.008 ms/op
Iteration   1: 4.074 ±(99.9%) 0.010 ms/op
Iteration   2: 3.983 ±(99.9%) 0.005 ms/op
Iteration   3: 3.914 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.990 ±(99.9%) 1.462 ms/op [Average]
  (min, avg, max) = (3.914, 3.990, 4.074), stdev = 0.080
  CI (99.9%): [2.529, 5.452] (assumes normal distribution)


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
# Warmup Iteration   1: 10.287 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.365 ±(99.9%) 0.009 ms/op
Iteration   1: 3.605 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.366 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   4.149 ms/op
                 createUser·p0.95:   5.775 ms/op
                 createUser·p0.99:   7.217 ms/op
                 createUser·p0.999:  11.798 ms/op
                 createUser·p0.9999: 22.675 ms/op
                 createUser·p1.00:   23.003 ms/op

Iteration   2: 3.423 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.430 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  11.330 ms/op
                 createUser·p0.9999: 24.150 ms/op
                 createUser·p1.00:   25.362 ms/op

Iteration   3: 3.343 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.481 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  17.944 ms/op
                 createUser·p0.9999: 26.435 ms/op
                 createUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277941
  mean =      3.453 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3087 
    [ 2.500,  5.000) = 265809 
    [ 5.000,  7.500) = 7756 
    [ 7.500, 10.000) = 874 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.481 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     11.583 ms/op
     p(99.9900) =     24.976 ms/op
     p(99.9990) =     27.103 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.538 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.010 ms/op
Iteration   1: 3.353 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.239 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   6.709 ms/op
                 existUser·p0.999:  19.354 ms/op
                 existUser·p0.9999: 25.148 ms/op
                 existUser·p1.00:   25.559 ms/op

Iteration   2: 3.331 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.025 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   4.190 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  10.092 ms/op
                 existUser·p0.9999: 24.504 ms/op
                 existUser·p1.00:   25.362 ms/op

Iteration   3: 3.380 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.686 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  18.943 ms/op
                 existUser·p0.9999: 25.821 ms/op
                 existUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286139
  mean =      3.355 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6312 
    [ 2.500,  5.000) = 273219 
    [ 5.000,  7.500) = 5725 
    [ 7.500, 10.000) = 544 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.025 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     11.958 ms/op
     p(99.9900) =     25.211 ms/op
     p(99.9990) =     26.490 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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
# Warmup Iteration   1: 8.966 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.704 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.513 ±(99.9%) 0.010 ms/op
Iteration   1: 3.461 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.497 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   7.029 ms/op
                 getUser·p0.999:  16.400 ms/op
                 getUser·p0.9999: 28.369 ms/op
                 getUser·p1.00:   29.983 ms/op

Iteration   2: 3.394 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.499 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   5.554 ms/op
                 getUser·p0.999:  22.729 ms/op
                 getUser·p0.9999: 28.514 ms/op
                 getUser·p1.00:   30.179 ms/op

Iteration   3: 3.331 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.704 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   6.078 ms/op
                 getUser·p0.999:  18.001 ms/op
                 getUser·p0.9999: 31.175 ms/op
                 getUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282599
  mean =      3.395 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1524 
    [ 2.500,  5.000) = 271597 
    [ 5.000,  7.500) = 8216 
    [ 7.500, 10.000) = 822 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.497 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      6.324 ms/op
     p(99.9000) =     16.400 ms/op
     p(99.9900) =     29.719 ms/op
     p(99.9990) =     31.835 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


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
# Warmup Iteration   1: 12.076 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.367 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.130 ±(99.9%) 0.014 ms/op
Iteration   1: 3.999 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.524 ms/op
                 listUser·p0.999:  21.068 ms/op
                 listUser·p0.9999: 29.753 ms/op
                 listUser·p1.00:   33.292 ms/op

Iteration   2: 3.917 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  15.440 ms/op
                 listUser·p0.9999: 17.760 ms/op
                 listUser·p1.00:   17.859 ms/op

Iteration   3: 3.954 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.578 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  15.582 ms/op
                 listUser·p0.9999: 19.756 ms/op
                 listUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242629
  mean =      3.956 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 233911 
    [ 5.000,  7.500) = 6714 
    [ 7.500, 10.000) = 1151 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 231 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     16.341 ms/op
     p(99.9900) =     25.869 ms/op
     p(99.9990) =     30.002 ms/op
     p(99.9999) =     33.292 ms/op
    p(100.0000) =     33.292 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.439 ± 4.346  ops/ms
ClientPb.existUser                       thrpt       3   9.736 ± 3.433  ops/ms
ClientPb.getUser                         thrpt       3   9.351 ± 3.921  ops/ms
ClientPb.listUser                        thrpt       3   7.895 ± 1.161  ops/ms
ClientPb.createUser                       avgt       3   3.279 ± 1.574   ms/op
ClientPb.existUser                        avgt       3   3.280 ± 0.613   ms/op
ClientPb.getUser                          avgt       3   3.380 ± 0.977   ms/op
ClientPb.listUser                         avgt       3   3.990 ± 1.462   ms/op
ClientPb.createUser                     sample  277941   3.453 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.481           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.277           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.898           ms/op
ClientPb.createUser:createUser·p0.999   sample          11.583           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.976           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.263           ms/op
ClientPb.existUser                      sample  286139   3.355 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.025           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.186           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.005           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.958           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.211           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.935           ms/op
ClientPb.getUser                        sample  282599   3.395 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.497           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.248           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.699           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.324           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.400           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.719           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.178           ms/op
ClientPb.listUser                       sample  242629   3.956 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.578           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.813           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.776           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.053           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.341           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.869           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.292           ms/op
