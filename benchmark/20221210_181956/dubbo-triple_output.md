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
# Warmup Iteration   1: 2.071 ops/ms
# Warmup Iteration   2: 5.873 ops/ms
# Warmup Iteration   3: 8.759 ops/ms
Iteration   1: 9.228 ops/ms
Iteration   2: 9.020 ops/ms
Iteration   3: 9.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.236 ±(99.9%) 4.022 ops/ms [Average]
  (min, avg, max) = (9.020, 9.236, 9.461), stdev = 0.220
  CI (99.9%): [5.214, 13.259] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.252 ops/ms
# Warmup Iteration   2: 8.880 ops/ms
# Warmup Iteration   3: 9.548 ops/ms
Iteration   1: 9.804 ops/ms
Iteration   2: 10.210 ops/ms
Iteration   3: 9.964 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.993 ±(99.9%) 3.731 ops/ms [Average]
  (min, avg, max) = (9.804, 9.993, 10.210), stdev = 0.204
  CI (99.9%): [6.262, 13.724] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.989 ops/ms
# Warmup Iteration   2: 8.455 ops/ms
# Warmup Iteration   3: 9.130 ops/ms
Iteration   1: 9.303 ops/ms
Iteration   2: 9.412 ops/ms
Iteration   3: 9.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.303 ±(99.9%) 1.990 ops/ms [Average]
  (min, avg, max) = (9.194, 9.303, 9.412), stdev = 0.109
  CI (99.9%): [7.313, 11.293] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.804 ops/ms
# Warmup Iteration   2: 7.156 ops/ms
# Warmup Iteration   3: 7.747 ops/ms
Iteration   1: 8.225 ops/ms
Iteration   2: 8.198 ops/ms
Iteration   3: 7.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.123 ±(99.9%) 2.792 ops/ms [Average]
  (min, avg, max) = (7.947, 8.123, 8.225), stdev = 0.153
  CI (99.9%): [5.332, 10.915] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.774 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.657 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.527 ±(99.9%) 0.004 ms/op
Iteration   1: 3.380 ±(99.9%) 0.012 ms/op
Iteration   2: 3.443 ±(99.9%) 0.008 ms/op
Iteration   3: 3.359 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.394 ±(99.9%) 0.793 ms/op [Average]
  (min, avg, max) = (3.359, 3.394, 3.443), stdev = 0.043
  CI (99.9%): [2.601, 4.187] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.404 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.604 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.009 ms/op
Iteration   1: 3.226 ±(99.9%) 0.007 ms/op
Iteration   2: 3.275 ±(99.9%) 0.011 ms/op
Iteration   3: 3.216 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.239 ±(99.9%) 0.577 ms/op [Average]
  (min, avg, max) = (3.216, 3.239, 3.275), stdev = 0.032
  CI (99.9%): [2.662, 3.816] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.039 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.710 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.551 ±(99.9%) 0.003 ms/op
Iteration   1: 3.428 ±(99.9%) 0.003 ms/op
Iteration   2: 3.373 ±(99.9%) 0.006 ms/op
Iteration   3: 3.325 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.376 ±(99.9%) 0.939 ms/op [Average]
  (min, avg, max) = (3.325, 3.376, 3.428), stdev = 0.051
  CI (99.9%): [2.437, 4.315] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.423 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.891 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.105 ±(99.9%) 0.007 ms/op
Iteration   1: 3.945 ±(99.9%) 0.012 ms/op
Iteration   2: 3.858 ±(99.9%) 0.011 ms/op
Iteration   3: 3.984 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.929 ±(99.9%) 1.181 ms/op [Average]
  (min, avg, max) = (3.858, 3.929, 3.984), stdev = 0.065
  CI (99.9%): [2.748, 5.110] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 11.238 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.298 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.890 ±(99.9%) 0.013 ms/op
Iteration   1: 3.433 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.582 ms/op
                 createUser·p0.999:  17.624 ms/op
                 createUser·p0.9999: 21.092 ms/op
                 createUser·p1.00:   22.053 ms/op

Iteration   2: 3.436 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.047 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   5.352 ms/op
                 createUser·p0.999:  19.785 ms/op
                 createUser·p0.9999: 23.976 ms/op
                 createUser·p1.00:   24.609 ms/op

Iteration   3: 3.578 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.731 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.166 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  19.172 ms/op
                 createUser·p0.9999: 29.985 ms/op
                 createUser·p1.00:   30.638 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275682
  mean =      3.481 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11219 
    [ 2.500,  5.000) = 259482 
    [ 5.000,  7.500) = 4211 
    [ 7.500, 10.000) = 363 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     18.819 ms/op
     p(99.9900) =     28.457 ms/op
     p(99.9990) =     30.161 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.012 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.467 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.009 ms/op
Iteration   1: 3.239 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.253 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  8.331 ms/op
                 existUser·p0.9999: 20.661 ms/op
                 existUser·p1.00:   21.398 ms/op

Iteration   2: 3.273 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.450 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   5.890 ms/op
                 existUser·p0.999:  11.952 ms/op
                 existUser·p0.9999: 22.042 ms/op
                 existUser·p1.00:   22.741 ms/op

Iteration   3: 3.274 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.112 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   5.517 ms/op
                 existUser·p0.999:  12.889 ms/op
                 existUser·p0.9999: 24.551 ms/op
                 existUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294148
  mean =      3.262 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24913 
    [ 2.500,  5.000) = 264005 
    [ 5.000,  7.500) = 4372 
    [ 7.500, 10.000) = 535 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     11.747 ms/op
     p(99.9900) =     24.063 ms/op
     p(99.9990) =     24.678 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.915 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.513 ±(99.9%) 0.011 ms/op
Iteration   1: 3.461 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.382 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  17.907 ms/op
                 getUser·p0.9999: 20.079 ms/op
                 getUser·p1.00:   20.611 ms/op

Iteration   2: 3.355 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.649 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   5.513 ms/op
                 getUser·p0.999:  18.973 ms/op
                 getUser·p0.9999: 21.872 ms/op
                 getUser·p1.00:   23.003 ms/op

Iteration   3: 3.347 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.421 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  18.728 ms/op
                 getUser·p0.9999: 28.305 ms/op
                 getUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 283313
  mean =      3.387 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5394 
    [ 2.500,  5.000) = 270739 
    [ 5.000,  7.500) = 6207 
    [ 7.500, 10.000) = 512 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.382 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     17.947 ms/op
     p(99.9900) =     26.313 ms/op
     p(99.9990) =     28.803 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.257 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.352 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.090 ±(99.9%) 0.013 ms/op
Iteration   1: 4.124 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.665 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   6.226 ms/op
                 listUser·p0.99:   8.102 ms/op
                 listUser·p0.999:  18.037 ms/op
                 listUser·p0.9999: 22.625 ms/op
                 listUser·p1.00:   23.691 ms/op

Iteration   2: 3.928 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.776 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  15.973 ms/op
                 listUser·p0.9999: 19.085 ms/op
                 listUser·p1.00:   19.300 ms/op

Iteration   3: 3.933 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.398 ms/op
                 listUser·p0.999:  15.090 ms/op
                 listUser·p0.9999: 24.248 ms/op
                 listUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240383
  mean =      3.993 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 229762 
    [ 5.000,  7.500) = 7930 
    [ 7.500, 10.000) = 1607 
    [10.000, 12.500) = 556 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 153 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.665 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      7.709 ms/op
     p(99.9000) =     16.218 ms/op
     p(99.9900) =     22.872 ms/op
     p(99.9990) =     24.301 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.236 ± 4.022  ops/ms
ClientPb.existUser                       thrpt       3   9.993 ± 3.731  ops/ms
ClientPb.getUser                         thrpt       3   9.303 ± 1.990  ops/ms
ClientPb.listUser                        thrpt       3   8.123 ± 2.792  ops/ms
ClientPb.createUser                       avgt       3   3.394 ± 0.793   ms/op
ClientPb.existUser                        avgt       3   3.239 ± 0.577   ms/op
ClientPb.getUser                          avgt       3   3.376 ± 0.939   ms/op
ClientPb.listUser                         avgt       3   3.929 ± 1.181   ms/op
ClientPb.createUser                     sample  275682   3.481 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.731           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.379           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.309           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.595           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.819           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.457           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.638           ms/op
ClientPb.existUser                      sample  294148   3.262 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.112           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.232           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.494           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.903           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.644           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.747           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.063           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.969           ms/op
ClientPb.getUser                        sample  283313   3.387 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.382           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.285           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.744           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.002           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.849           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.947           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.313           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.000           ms/op
ClientPb.listUser                       sample  240383   3.993 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.665           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.743           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.709           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.218           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.872           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.379           ms/op
