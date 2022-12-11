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
# Warmup Iteration   1: 2.074 ops/ms
# Warmup Iteration   2: 5.168 ops/ms
# Warmup Iteration   3: 8.142 ops/ms
Iteration   1: 8.801 ops/ms
Iteration   2: 9.330 ops/ms
Iteration   3: 9.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.202 ±(99.9%) 6.483 ops/ms [Average]
  (min, avg, max) = (8.801, 9.202, 9.476), stdev = 0.355
  CI (99.9%): [2.720, 15.685] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.678 ops/ms
# Warmup Iteration   2: 8.712 ops/ms
# Warmup Iteration   3: 9.446 ops/ms
Iteration   1: 9.845 ops/ms
Iteration   2: 10.017 ops/ms
Iteration   3: 9.975 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.946 ±(99.9%) 1.632 ops/ms [Average]
  (min, avg, max) = (9.845, 9.946, 10.017), stdev = 0.089
  CI (99.9%): [8.313, 11.578] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.698 ops/ms
# Warmup Iteration   2: 8.095 ops/ms
# Warmup Iteration   3: 9.247 ops/ms
Iteration   1: 9.005 ops/ms
Iteration   2: 9.552 ops/ms
Iteration   3: 9.443 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.333 ±(99.9%) 5.283 ops/ms [Average]
  (min, avg, max) = (9.005, 9.333, 9.552), stdev = 0.290
  CI (99.9%): [4.050, 14.616] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.576 ops/ms
# Warmup Iteration   2: 7.329 ops/ms
# Warmup Iteration   3: 7.847 ops/ms
Iteration   1: 7.740 ops/ms
Iteration   2: 7.892 ops/ms
Iteration   3: 7.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.857 ±(99.9%) 1.899 ops/ms [Average]
  (min, avg, max) = (7.740, 7.857, 7.940), stdev = 0.104
  CI (99.9%): [5.959, 9.756] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 11.704 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.832 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.626 ±(99.9%) 0.005 ms/op
Iteration   1: 3.369 ±(99.9%) 0.003 ms/op
Iteration   2: 3.392 ±(99.9%) 0.003 ms/op
Iteration   3: 3.343 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.368 ±(99.9%) 0.447 ms/op [Average]
  (min, avg, max) = (3.343, 3.368, 3.392), stdev = 0.025
  CI (99.9%): [2.921, 3.815] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.182 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.628 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.386 ±(99.9%) 0.003 ms/op
Iteration   1: 3.208 ±(99.9%) 0.013 ms/op
Iteration   2: 3.257 ±(99.9%) 0.008 ms/op
Iteration   3: 3.222 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.229 ±(99.9%) 0.460 ms/op [Average]
  (min, avg, max) = (3.208, 3.229, 3.257), stdev = 0.025
  CI (99.9%): [2.768, 3.689] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.432 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.149 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.590 ±(99.9%) 0.005 ms/op
Iteration   1: 3.486 ±(99.9%) 0.006 ms/op
Iteration   2: 3.452 ±(99.9%) 0.008 ms/op
Iteration   3: 3.243 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.394 ±(99.9%) 2.408 ms/op [Average]
  (min, avg, max) = (3.243, 3.394, 3.486), stdev = 0.132
  CI (99.9%): [0.986, 5.802] (assumes normal distribution)


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
# Warmup Iteration   1: 10.042 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.243 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.064 ±(99.9%) 0.006 ms/op
Iteration   1: 3.998 ±(99.9%) 0.015 ms/op
Iteration   2: 3.852 ±(99.9%) 0.014 ms/op
Iteration   3: 3.920 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.923 ±(99.9%) 1.338 ms/op [Average]
  (min, avg, max) = (3.852, 3.923, 3.998), stdev = 0.073
  CI (99.9%): [2.585, 5.262] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.783 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.933 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.731 ±(99.9%) 0.012 ms/op
Iteration   1: 3.334 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  21.686 ms/op
                 createUser·p0.9999: 25.441 ms/op
                 createUser·p1.00:   26.247 ms/op

Iteration   2: 3.362 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.270 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  23.889 ms/op
                 createUser·p0.9999: 26.444 ms/op
                 createUser·p1.00:   27.558 ms/op

Iteration   3: 3.470 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.358 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  17.071 ms/op
                 createUser·p0.9999: 26.076 ms/op
                 createUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283487
  mean =      3.388 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13165 
    [ 2.500,  5.000) = 265236 
    [ 5.000,  7.500) = 4204 
    [ 7.500, 10.000) = 385 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 123 
    [25.000, 27.500) = 93 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     26.083 ms/op
     p(99.9990) =     27.438 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


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
# Warmup Iteration   1: 7.656 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.567 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.389 ±(99.9%) 0.009 ms/op
Iteration   1: 3.269 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.464 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   5.690 ms/op
                 existUser·p0.999:  11.076 ms/op
                 existUser·p0.9999: 26.910 ms/op
                 existUser·p1.00:   27.951 ms/op

Iteration   2: 3.204 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  10.507 ms/op
                 existUser·p0.9999: 23.331 ms/op
                 existUser·p1.00:   24.052 ms/op

Iteration   3: 3.291 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  11.731 ms/op
                 existUser·p0.9999: 35.670 ms/op
                 existUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294915
  mean =      3.254 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17818 
    [ 2.500,  5.000) = 271524 
    [ 5.000,  7.500) = 4807 
    [ 7.500, 10.000) = 396 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     11.488 ms/op
     p(99.9900) =     35.030 ms/op
     p(99.9990) =     36.179 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


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
# Warmup Iteration   1: 10.491 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 3.818 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.506 ±(99.9%) 0.011 ms/op
Iteration   1: 3.454 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.993 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   6.593 ms/op
                 getUser·p0.999:  19.647 ms/op
                 getUser·p0.9999: 33.423 ms/op
                 getUser·p1.00:   36.045 ms/op

Iteration   2: 3.457 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.360 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   7.365 ms/op
                 getUser·p0.999:  19.838 ms/op
                 getUser·p0.9999: 22.658 ms/op
                 getUser·p1.00:   23.757 ms/op

Iteration   3: 3.380 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.440 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   5.930 ms/op
                 getUser·p0.999:  19.149 ms/op
                 getUser·p0.9999: 25.410 ms/op
                 getUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279928
  mean =      3.430 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2288 
    [ 2.500,  5.000) = 269352 
    [ 5.000,  7.500) = 6817 
    [ 7.500, 10.000) = 931 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 155 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      7.018 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     32.866 ms/op
     p(99.9990) =     36.045 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


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
# Warmup Iteration   1: 10.959 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.473 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.127 ±(99.9%) 0.012 ms/op
Iteration   1: 4.018 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.007 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.750 ms/op
                 listUser·p0.999:  19.996 ms/op
                 listUser·p0.9999: 25.597 ms/op
                 listUser·p1.00:   26.608 ms/op

Iteration   2: 3.940 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  15.499 ms/op
                 listUser·p0.9999: 16.531 ms/op
                 listUser·p1.00:   16.777 ms/op

Iteration   3: 3.866 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  15.483 ms/op
                 listUser·p0.9999: 22.428 ms/op
                 listUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243588
  mean =      3.941 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 235922 
    [ 5.000,  7.500) = 5509 
    [ 7.500, 10.000) = 1254 
    [10.000, 12.500) = 289 
    [12.500, 15.000) = 264 
    [15.000, 17.500) = 156 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      2.007 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.186 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     16.063 ms/op
     p(99.9900) =     24.576 ms/op
     p(99.9990) =     26.051 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.202 ± 6.483  ops/ms
ClientPb.existUser                       thrpt       3   9.946 ± 1.632  ops/ms
ClientPb.getUser                         thrpt       3   9.333 ± 5.283  ops/ms
ClientPb.listUser                        thrpt       3   7.857 ± 1.899  ops/ms
ClientPb.createUser                       avgt       3   3.368 ± 0.447   ms/op
ClientPb.existUser                        avgt       3   3.229 ± 0.460   ms/op
ClientPb.getUser                          avgt       3   3.394 ± 2.408   ms/op
ClientPb.listUser                         avgt       3   3.923 ± 1.338   ms/op
ClientPb.createUser                     sample  283487   3.388 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.841           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.326           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.100           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.669           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.138           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.083           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.558           ms/op
ClientPb.existUser                      sample  294915   3.254 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.116           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.187           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.555           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.965           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.579           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.488           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.030           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.372           ms/op
ClientPb.getUser                        sample  279928   3.430 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.360           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.289           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.740           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.030           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.018           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.366           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.866           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.045           ms/op
ClientPb.listUser                       sample  243588   3.941 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.007           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.186           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.299           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.063           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.576           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.608           ms/op
