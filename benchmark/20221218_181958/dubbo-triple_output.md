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
# Warmup Iteration   1: 2.943 ops/ms
# Warmup Iteration   2: 6.440 ops/ms
# Warmup Iteration   3: 9.362 ops/ms
Iteration   1: 9.855 ops/ms
Iteration   2: 9.447 ops/ms
Iteration   3: 10.099 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.800 ±(99.9%) 6.009 ops/ms [Average]
  (min, avg, max) = (9.447, 9.800, 10.099), stdev = 0.329
  CI (99.9%): [3.791, 15.809] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 3.742 ops/ms
# Warmup Iteration   2: 9.393 ops/ms
# Warmup Iteration   3: 10.617 ops/ms
Iteration   1: 10.726 ops/ms
Iteration   2: 10.392 ops/ms
Iteration   3: 10.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.625 ±(99.9%) 3.685 ops/ms [Average]
  (min, avg, max) = (10.392, 10.625, 10.756), stdev = 0.202
  CI (99.9%): [6.940, 14.310] (assumes normal distribution)


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
# Warmup Iteration   1: 3.846 ops/ms
# Warmup Iteration   2: 9.205 ops/ms
# Warmup Iteration   3: 9.568 ops/ms
Iteration   1: 10.035 ops/ms
Iteration   2: 10.208 ops/ms
Iteration   3: 10.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.141 ±(99.9%) 1.705 ops/ms [Average]
  (min, avg, max) = (10.035, 10.141, 10.208), stdev = 0.093
  CI (99.9%): [8.437, 11.846] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.646 ops/ms
# Warmup Iteration   2: 7.786 ops/ms
# Warmup Iteration   3: 8.196 ops/ms
Iteration   1: 8.425 ops/ms
Iteration   2: 8.768 ops/ms
Iteration   3: 8.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.453 ±(99.9%) 5.508 ops/ms [Average]
  (min, avg, max) = (8.166, 8.453, 8.768), stdev = 0.302
  CI (99.9%): [2.945, 13.960] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.816 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.567 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.329 ±(99.9%) 0.006 ms/op
Iteration   1: 3.116 ±(99.9%) 0.009 ms/op
Iteration   2: 3.254 ±(99.9%) 0.007 ms/op
Iteration   3: 3.138 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.170 ±(99.9%) 1.356 ms/op [Average]
  (min, avg, max) = (3.116, 3.170, 3.254), stdev = 0.074
  CI (99.9%): [1.814, 4.525] (assumes normal distribution)


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
# Warmup Iteration   1: 6.605 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.002 ms/op
Iteration   1: 3.160 ±(99.9%) 0.005 ms/op
Iteration   2: 3.069 ±(99.9%) 0.005 ms/op
Iteration   3: 3.106 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.112 ±(99.9%) 0.836 ms/op [Average]
  (min, avg, max) = (3.069, 3.112, 3.160), stdev = 0.046
  CI (99.9%): [2.276, 3.947] (assumes normal distribution)


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
# Warmup Iteration   1: 7.873 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.568 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.449 ±(99.9%) 0.003 ms/op
Iteration   1: 3.134 ±(99.9%) 0.003 ms/op
Iteration   2: 3.109 ±(99.9%) 0.006 ms/op
Iteration   3: 3.094 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.113 ±(99.9%) 0.371 ms/op [Average]
  (min, avg, max) = (3.094, 3.113, 3.134), stdev = 0.020
  CI (99.9%): [2.741, 3.484] (assumes normal distribution)


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
# Warmup Iteration   1: 8.935 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.115 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.709 ±(99.9%) 0.005 ms/op
Iteration   1: 3.676 ±(99.9%) 0.006 ms/op
Iteration   2: 3.777 ±(99.9%) 0.006 ms/op
Iteration   3: 3.712 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.722 ±(99.9%) 0.935 ms/op [Average]
  (min, avg, max) = (3.676, 3.722, 3.777), stdev = 0.051
  CI (99.9%): [2.786, 4.657] (assumes normal distribution)


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
# Warmup Iteration   1: 8.376 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.525 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.008 ms/op
Iteration   1: 3.076 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.247 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  11.848 ms/op
                 createUser·p0.9999: 18.659 ms/op
                 createUser·p1.00:   20.414 ms/op

Iteration   2: 3.076 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.292 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.228 ms/op
                 createUser·p0.95:   3.473 ms/op
                 createUser·p0.99:   4.752 ms/op
                 createUser·p0.999:  12.059 ms/op
                 createUser·p0.9999: 20.696 ms/op
                 createUser·p1.00:   21.660 ms/op

Iteration   3: 3.279 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.141 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  7.815 ms/op
                 createUser·p0.9999: 16.809 ms/op
                 createUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 305444
  mean =      3.141 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22229 
    [ 2.500,  5.000) = 279150 
    [ 5.000,  7.500) = 3376 
    [ 7.500, 10.000) = 333 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      5.317 ms/op
     p(99.9000) =     12.059 ms/op
     p(99.9900) =     20.102 ms/op
     p(99.9990) =     21.561 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


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
# Warmup Iteration   1: 6.604 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 3.264 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.007 ms/op
Iteration   1: 3.020 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.910 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  10.174 ms/op
                 existUser·p0.9999: 23.396 ms/op
                 existUser·p1.00:   25.166 ms/op

Iteration   2: 3.022 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.567 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  9.290 ms/op
                 existUser·p0.9999: 21.214 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   3: 3.013 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.883 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.371 ms/op
                 existUser·p0.99:   4.812 ms/op
                 existUser·p0.999:  13.533 ms/op
                 existUser·p0.9999: 22.950 ms/op
                 existUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 318076
  mean =      3.018 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23380 
    [ 2.500,  5.000) = 290826 
    [ 5.000,  7.500) = 3255 
    [ 7.500, 10.000) = 215 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.228 ms/op
     p(95.0000) =      3.482 ms/op
     p(99.0000) =      5.128 ms/op
     p(99.9000) =     12.288 ms/op
     p(99.9900) =     23.167 ms/op
     p(99.9990) =     25.062 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 7.176 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.474 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.299 ±(99.9%) 0.010 ms/op
Iteration   1: 3.262 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.782 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.182 ms/op
                 getUser·p0.99:   6.209 ms/op
                 getUser·p0.999:  15.679 ms/op
                 getUser·p0.9999: 19.884 ms/op
                 getUser·p1.00:   20.382 ms/op

Iteration   2: 3.153 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   5.366 ms/op
                 getUser·p0.999:  11.754 ms/op
                 getUser·p0.9999: 20.999 ms/op
                 getUser·p1.00:   23.298 ms/op

Iteration   3: 3.303 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.317 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.020 ms/op
                 getUser·p0.999:  11.609 ms/op
                 getUser·p0.9999: 20.434 ms/op
                 getUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296346
  mean =      3.238 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12466 
    [ 2.500,  5.000) = 276332 
    [ 5.000,  7.500) = 6303 
    [ 7.500, 10.000) = 789 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 189 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     14.879 ms/op
     p(99.9900) =     20.382 ms/op
     p(99.9990) =     23.104 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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
# Warmup Iteration   1: 8.493 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.179 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.843 ±(99.9%) 0.011 ms/op
Iteration   1: 3.739 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.064 ms/op
                 listUser·p0.50:   3.547 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  15.280 ms/op
                 listUser·p0.9999: 19.333 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   2: 3.663 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   3.551 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  13.451 ms/op
                 listUser·p0.9999: 14.787 ms/op
                 listUser·p1.00:   15.041 ms/op

Iteration   3: 3.752 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.575 ms/op
                 listUser·p0.50:   3.559 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  13.206 ms/op
                 listUser·p0.9999: 18.645 ms/op
                 listUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258254
  mean =      3.717 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 249633 
    [ 5.000,  7.500) = 6728 
    [ 7.500, 10.000) = 1180 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 348 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.575 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     14.090 ms/op
     p(99.9900) =     18.815 ms/op
     p(99.9990) =     19.934 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.800 ± 6.009  ops/ms
ClientPb.existUser                       thrpt       3  10.625 ± 3.685  ops/ms
ClientPb.getUser                         thrpt       3  10.141 ± 1.705  ops/ms
ClientPb.listUser                        thrpt       3   8.453 ± 5.508  ops/ms
ClientPb.createUser                       avgt       3   3.170 ± 1.356   ms/op
ClientPb.existUser                        avgt       3   3.112 ± 0.836   ms/op
ClientPb.getUser                          avgt       3   3.113 ± 0.371   ms/op
ClientPb.listUser                         avgt       3   3.722 ± 0.935   ms/op
ClientPb.createUser                     sample  305444   3.141 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.141           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.633           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.317           ms/op
ClientPb.createUser:createUser·p0.999   sample          12.059           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.102           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.660           ms/op
ClientPb.existUser                      sample  318076   3.018 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.883           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.482           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.128           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.288           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.167           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.166           ms/op
ClientPb.getUser                        sample  296346   3.238 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.782           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.682           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.784           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.879           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.382           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.298           ms/op
ClientPb.listUser                       sample  258254   3.717 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.575           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.555           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.141           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.988           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.090           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.815           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.332           ms/op
