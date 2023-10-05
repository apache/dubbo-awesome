# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.915 ops/ms
# Warmup Iteration   2: 6.127 ops/ms
# Warmup Iteration   3: 8.470 ops/ms
Iteration   1: 9.083 ops/ms
Iteration   2: 9.090 ops/ms
Iteration   3: 9.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.126 ±(99.9%) 1.252 ops/ms [Average]
  (min, avg, max) = (9.083, 9.126, 9.205), stdev = 0.069
  CI (99.9%): [7.873, 10.378] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.694 ops/ms
# Warmup Iteration   2: 8.185 ops/ms
# Warmup Iteration   3: 9.422 ops/ms
Iteration   1: 9.687 ops/ms
Iteration   2: 9.747 ops/ms
Iteration   3: 9.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.686 ±(99.9%) 1.106 ops/ms [Average]
  (min, avg, max) = (9.625, 9.686, 9.747), stdev = 0.061
  CI (99.9%): [8.580, 10.793] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.628 ops/ms
# Warmup Iteration   2: 8.315 ops/ms
# Warmup Iteration   3: 8.777 ops/ms
Iteration   1: 9.058 ops/ms
Iteration   2: 8.844 ops/ms
Iteration   3: 9.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.012 ±(99.9%) 2.743 ops/ms [Average]
  (min, avg, max) = (8.844, 9.012, 9.134), stdev = 0.150
  CI (99.9%): [6.269, 11.754] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.332 ops/ms
# Warmup Iteration   2: 6.668 ops/ms
# Warmup Iteration   3: 7.552 ops/ms
Iteration   1: 7.358 ops/ms
Iteration   2: 7.695 ops/ms
Iteration   3: 7.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.601 ±(99.9%) 3.876 ops/ms [Average]
  (min, avg, max) = (7.358, 7.601, 7.750), stdev = 0.212
  CI (99.9%): [3.725, 11.477] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 11.411 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.800 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.730 ±(99.9%) 0.004 ms/op
Iteration   1: 3.579 ±(99.9%) 0.004 ms/op
Iteration   2: 3.578 ±(99.9%) 0.003 ms/op
Iteration   3: 3.559 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.572 ±(99.9%) 0.203 ms/op [Average]
  (min, avg, max) = (3.559, 3.572, 3.579), stdev = 0.011
  CI (99.9%): [3.369, 3.775] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.932 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.652 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.492 ±(99.9%) 0.002 ms/op
Iteration   1: 3.453 ±(99.9%) 0.003 ms/op
Iteration   2: 3.568 ±(99.9%) 0.004 ms/op
Iteration   3: 3.489 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.503 ±(99.9%) 1.079 ms/op [Average]
  (min, avg, max) = (3.453, 3.503, 3.568), stdev = 0.059
  CI (99.9%): [2.424, 4.583] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.016 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.661 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.636 ±(99.9%) 0.006 ms/op
Iteration   1: 3.454 ±(99.9%) 0.003 ms/op
Iteration   2: 3.456 ±(99.9%) 0.003 ms/op
Iteration   3: 3.461 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.457 ±(99.9%) 0.068 ms/op [Average]
  (min, avg, max) = (3.454, 3.457, 3.461), stdev = 0.004
  CI (99.9%): [3.389, 3.525] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 12.312 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.518 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.227 ±(99.9%) 0.008 ms/op
Iteration   1: 4.205 ±(99.9%) 0.005 ms/op
Iteration   2: 4.149 ±(99.9%) 0.008 ms/op
Iteration   3: 4.202 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.185 ±(99.9%) 0.574 ms/op [Average]
  (min, avg, max) = (4.149, 4.185, 4.205), stdev = 0.031
  CI (99.9%): [3.611, 4.759] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 10.082 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.004 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.610 ±(99.9%) 0.011 ms/op
Iteration   1: 3.528 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.046 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  21.279 ms/op
                 createUser·p0.9999: 25.319 ms/op
                 createUser·p1.00:   27.656 ms/op

Iteration   2: 3.597 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.221 ms/op
                 createUser·p0.50:   3.465 ms/op
                 createUser·p0.90:   4.170 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   6.160 ms/op
                 createUser·p0.999:  13.059 ms/op
                 createUser·p0.9999: 26.877 ms/op
                 createUser·p1.00:   27.623 ms/op

Iteration   3: 3.528 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.501 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  22.839 ms/op
                 createUser·p0.9999: 29.262 ms/op
                 createUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270472
  mean =      3.551 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4369 
    [ 2.500,  5.000) = 261151 
    [ 5.000,  7.500) = 3836 
    [ 7.500, 10.000) = 443 
    [10.000, 12.500) = 281 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.046 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     15.466 ms/op
     p(99.9900) =     28.508 ms/op
     p(99.9990) =     29.971 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.004 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.642 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.443 ±(99.9%) 0.009 ms/op
Iteration   1: 3.348 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.393 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  21.314 ms/op
                 existUser·p0.9999: 24.303 ms/op
                 existUser·p1.00:   25.133 ms/op

Iteration   2: 3.401 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.309 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   5.800 ms/op
                 existUser·p0.999:  13.071 ms/op
                 existUser·p0.9999: 25.985 ms/op
                 existUser·p1.00:   26.313 ms/op

Iteration   3: 3.400 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.360 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  23.591 ms/op
                 existUser·p0.9999: 29.529 ms/op
                 existUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283652
  mean =      3.383 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7805 
    [ 2.500,  5.000) = 270808 
    [ 5.000,  7.500) = 4033 
    [ 7.500, 10.000) = 363 
    [10.000, 12.500) = 315 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.309 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     13.195 ms/op
     p(99.9900) =     28.279 ms/op
     p(99.9990) =     30.026 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.337 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.932 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.640 ±(99.9%) 0.012 ms/op
Iteration   1: 3.515 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.019 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   7.023 ms/op
                 getUser·p0.999:  18.190 ms/op
                 getUser·p0.9999: 32.866 ms/op
                 getUser·p1.00:   33.686 ms/op

Iteration   2: 3.457 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.479 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   5.636 ms/op
                 getUser·p0.999:  13.369 ms/op
                 getUser·p0.9999: 26.698 ms/op
                 getUser·p1.00:   27.492 ms/op

Iteration   3: 3.541 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.360 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   7.053 ms/op
                 getUser·p0.999:  24.713 ms/op
                 getUser·p0.9999: 29.194 ms/op
                 getUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273823
  mean =      3.504 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3302 
    [ 2.500,  5.000) = 261287 
    [ 5.000,  7.500) = 7885 
    [ 7.500, 10.000) = 804 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 103 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     16.380 ms/op
     p(99.9900) =     29.753 ms/op
     p(99.9990) =     33.301 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.584 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.679 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.364 ±(99.9%) 0.013 ms/op
Iteration   1: 4.416 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.726 ms/op
                 listUser·p0.50:   4.252 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.243 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  22.512 ms/op
                 listUser·p0.9999: 25.158 ms/op
                 listUser·p1.00:   26.214 ms/op

Iteration   2: 4.226 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.425 ms/op
                 listUser·p0.50:   4.084 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   7.512 ms/op
                 listUser·p0.999:  16.843 ms/op
                 listUser·p0.9999: 19.478 ms/op
                 listUser·p1.00:   21.922 ms/op

Iteration   3: 4.259 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   4.133 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.038 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  15.988 ms/op
                 listUser·p0.9999: 17.039 ms/op
                 listUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 223180
  mean =      4.299 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 211062 
    [ 5.000,  7.500) = 9252 
    [ 7.500, 10.000) = 1848 
    [10.000, 12.500) = 396 
    [12.500, 15.000) = 192 
    [15.000, 17.500) = 214 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.726 ms/op
     p(50.0000) =      4.153 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      7.791 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     24.271 ms/op
     p(99.9990) =     25.798 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.126 ± 1.252  ops/ms
ClientPb.existUser                       thrpt       3   9.686 ± 1.106  ops/ms
ClientPb.getUser                         thrpt       3   9.012 ± 2.743  ops/ms
ClientPb.listUser                        thrpt       3   7.601 ± 3.876  ops/ms
ClientPb.createUser                       avgt       3   3.572 ± 0.203   ms/op
ClientPb.existUser                        avgt       3   3.503 ± 1.079   ms/op
ClientPb.getUser                          avgt       3   3.457 ± 0.068   ms/op
ClientPb.listUser                         avgt       3   4.185 ± 0.574   ms/op
ClientPb.createUser                     sample  270472   3.551 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.046           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.428           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.358           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.890           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.466           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.508           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.573           ms/op
ClientPb.existUser                      sample  283652   3.383 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.309           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.297           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.014           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.800           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.195           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.279           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.179           ms/op
ClientPb.getUser                        sample  273823   3.504 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.360           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.351           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.873           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.380           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.753           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.686           ms/op
ClientPb.listUser                       sample  223180   4.299 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.726           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.153           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.743           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.046           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.791           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.941           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.271           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.214           ms/op
